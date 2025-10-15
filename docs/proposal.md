Course: ISN 4131 - Distributed Systems and Cloud Computing 
Student Name: Tamasang Jesse-Francis Mabu 
Matricule: ICTU20233738
Date: 14/10/2025
Topic: Smart Waste Collection Platform Proposal 

1. INTRODUCTION:
As the CEO of my company I am proposing a distributed waste collection service called "Trash it" that tackles a sanitation problem in our universities and neighborhoods across Cameroon. This service aims to provide households and students with a platform that connects them to local trash collectors easing the process of trash disposal while creating income opportunities for waste workers. 

The Problem:
In areas like the surroundings of ICT university where the people who live there are mostly students and staff of the school waste management or disposal is a challenge because the said individuals are mostly busy to get rid of the trash themselves . To add to this waste disposal point are too far from their homes and even HYSACAM workers and their trucks have proven to be inefficient judging from their rare availability. This makes these individuals to result to improper methods for disposing their waste or trash such as throwing trash in nearby bushes or streets which leads to environmental pollution.

Meanwhile there appears to be a whole informal network of young people who collect trash in these localities and charge small fees. But these workers often have difficulties finding customers because of their low visibility and lack a systematic way of operating and customers on the other hand lack a way of finding reliable workers to get their trash.

The Solution:
Trash it is a mobile and web-based platform that bridges that gap that exists between people who need their trash thrown appropriately and waste collectors who are readily available to get the job done. Users/customers can order/schedule pickups for their trash at their doorstep and pay collectors digitally upon collection of the trash all this through the app. Trash collectors on the other hand can get trash collection requests and navigate to the location of the pick up request and get paid through the app. 

2. SERVICE DESCRIPTION 
Core Features 
For Users:
-Request on-demand waste pickup or schedule recurring collections
-View available collectors nearby with their ratings and estimated arrival time
-Choose waste type (general waste, recyclables, organic waste)
-Make payments through integrated mobile money systems
-Rate collectors after service completion
-Track collector location in real-time during pickup

For Waste collectors:
-Receive pickup requests based on their location and availability
-Navigate to customer locations using built-in maps
-Confirm pickup completion and receive payment instantly
-Build reputation through customer ratings
-Access to a steady stream of customers without having to search door-to-door

For Administrators:
-Monitor all transactions and service requests
-Manage user and collector accounts
-Handle disputes and complaints
-Generate reports on waste collection patterns
-Coordinate with municipal waste management authorities

How it works 
1. A user opens the CleanConnect app and submits a waste collection request
2. The system identifies available collectors within the area
3. The nearest available collector receives a notification
4. The collector accepts the request and heads to the user's location
5. Upon arrival, the collector picks up the waste
6. User confirms pickup completion in the app
7. Payment is automatically processed from user to collector (with small platform commission)
8. Customer rates collector 

3. DISTRIBUTED SYSTEMS CHARACTERISTICS 
3.1 Scalability 
Trash it is designed to be highly scalable so as to accommodate the increasing workload that will come when the application will grow from being used in a neighborhood to an entire city and possibly nation wide.This level of scalability is going to be achieved through the implementation of cloud infrastructure, a micro service architecture, database sharing and the use of load balancers.

3.2 Fault Tolerance 
Trash it is designed to continue operating even if individual components fail. This is achieved through a couple of mechanisms like; 
-Server redundancy where multiple servers are utilized across different zones so when crashes another takes over without users noticing. 
-Data replication where databases are replicated in different geographic locations so that if one fails a replica takes over immediately.
-Payment Backup options where if the primary mobile payment method integrated fails alternatives should be used.
-Multiple independent collectors in an area where if one collector is unavailable the system immediately redirects the request to the nearest available collector.

3.3 Collaboration 
Trash it is also a highly collaborative distributed system where there multiple actors . Primary collaboration occurs between users(households, students ) and waste collectors . This is achieved and facilitated through the platform by ;
-Matching requests with appropriate collectors based on location, availability, and ratings
-Providing communication channels (in-app chat, call buttons)
-Establishing trust through verified profiles and rating systems
-Ensuring fair transactions through automated payment processing

Users can even collaborate among each other to organize bulk pick ups . Collectors can also collaborate with the waste management authorities for disposal of waste at official sites .

4. TECHNICAL ARCHITECTURE 
System Components 
Frontend Applications:
-User Mobile App (Android/iOS using React Native or Flutter)
-Collector Mobile App (optimized for low-end devices)
-Web Dashboard for administrators

Backend Services:
-Authentication Service (user/collector login and verification)
-Request Management Service (handles pickup requests)
-Matching Engine (connects users with appropriate collectors)
-Payment Processing Service (integrates with mobile money)
-Location Tracking Service (GPS and mapping)
-Notification Service (push notifications, SMS)
-Rating and Review Service

Data Storage:
-Primary Database (PostgreSQL for structured data)
-Caching Layer (Redis for frequently accessed data)
-File Storage (for profile pictures, receipts)

Third-Party Integrations:
-Mobile Money APIs (MTN MoMo, Orange Money)
-Mapping Services (Google Maps or OpenStreetMap)
-SMS Gateway (for notifications to feature phone users)

Infrastructure:
-Cloud Hosting 
-Monitoring and analytics tools

5. Business Model
-10% fee on each transaction 
-Users can subscribe for premium membership which grants them access to priority service and scheduled pickups.
-Anonymous waste generation data is sold to researchers, companies or individuals who may need this data.

6. RELEVANCE TO CAMEROON AND AFRICA
The Trash it service is relevant to my community and home Cameroon through the following ways;

-Waste management infrastructure has been unable to keep up with the rapid increase of waste production and creation in neighborhoods, towns and cities as seen with the as seen with the municipal waste collection service which doesn't reach some neighborhoods and rarely show up. Trash it provides a solution to support, collaborate with already existing systems.

-Young people in Cameroon struggle to find jobs .Trash it offers these young people a chance to make some income by working as trash collectors and receive a steady customer supply for steady income generation.

-Trash it reduces pollution in our environment due to its introduction of proper , affordable , convenient and efficient waste disposal methods.

7. CONCLUSION 
Trash it is a practical application of distributed systems principles to solve a real world problem affecting our communities in Cameroon and Africa at large.By implementing cloud computing, mobile technologies and collaborative networks, Trash it can make waste management more efficient , create income opportunities for informal young workers and contribute to a healthier urban environment. 

10. REFERENCES 

Tanenbaum, A. S., & Van Steen, M. (2007). Distributed Systems: Principles and Paradigms. Pearson Prentice Hall.

Coulouris, G., Dollimore, J., Kindberg, T., & Blair, G. (2012). Distributed Systems: Concepts and Design. Addison-Wesley.

Course materials: CS 4122 Distributed Systems and Cloud Computing, ICT University

Personal observations of waste management challenges in Yaoundé, Cameroon    