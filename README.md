# Benjamins
Android app to connect students and freelancers to event organizers

Motivation & Use Case

The application connects the event organizers who are in urgent need of people for their events with individuals who are willing to make a quick buck. Many events take place throughout the city where there is always shortage of staff for the event. Similarly, there are many people who have spare time and would love to earn some money over a day’s job. Our application provides the marketplace where these individuals meet the event planners within their desired location.
Suppose there is a wedding or a promotional event where there is immediate need for another 3-4 people. The event manager can then post a requirement on our app and various job seekers within a specified radius can view the same and take up the job. This rendezvous helped the event to be executed as desired and also helped people monetize their spare time.

Major Functionalities and User Experience

User is presented with a list of events within a distance specified by him/her. 
If interested, there will be something similar to a 3-way handshake between the event poster and the user. At the end of the event, the user will be paid.
Once the event is over, it will be removed from the database and both the user and the event planner will be asked to provide feedback for QoS

Underlying Architecture
There will be a server which maintains the overall app display, including which events to show and what information to be sent to both the user and the event poster. The job seeker and job poster will have customized UIs containing relevant information. Once there is confirmation from both sides for the job, the server will send confirmation notifications to both the parties using GCM. At the end of the event, both will be asked for feedback. The feedback will be recorded in database per user and per job poster which will be used to rate them for authenticity.

