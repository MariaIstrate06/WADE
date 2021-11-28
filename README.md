# TRASD WADe Project

FII's Master students WADe Traffic Sign Smart Detector project

## Task Description

Having several (snapshots of) video recordings – captured via a Webcam or uploaded by a user – regarding an urban route (frequently/randomly) followed by a person or a group of persons (e.g., by using a bike/car/bus), develop a (micro-)service-based Web system able to detect road/traffic signs marking this route (road, highway). This detection process could be performed automatically by using specific public APIs and/or by using user-reported info (for example, by using external crowdsourcing navigation services like Waze or alternatives). An ontology specified in OWL will be created and/or adapted to specify things of interest (mainly, a classification of road/traffic signs and their meanings and legal interpretations). For each recognized (category of) road sign, a SPARQL endpoint will offer various knowledge: meaning, type, legal regulations, relationships to other traffic signs, practical advices, context of use, comparisons, plus suggestions regarding user (driver/pedestrian) behavior.  
Study the [Comparison of European road signs](https://www.wikiwand.com/en/Comparison_of_European_road_signs).  
Additional resources:

- [Traffic Sign Detection Articles @ Google Scholar](https://scholar.google.com/scholar?hl=en&q=traffic+sign+detection&btnG=&oq=traffic+sign)
- [Traffic Sign Recognition Code Repositories @ GitHub](https://github.com/topics/traffic-sign-recognition)

## Team

- Denis Aenasoaei - denis.aenasoaei@yahoo.com
- Maria Istrate - mistrate06@gmail.com
- Cristi Rusu - cristirusu.99@gmail.com

## Solution Description

For solving the presented task we are going to build a Web Application based on microservices. The main components of the application will be:

### Backoffice API

- C#/.NET component that will offer endpoints for connecting the other components of the application and the database.

### Image Processing

- Video Recognition and Image Processing using Python, OpenCV and Tensorflow.

### Frontend Client

- Angular 10 Single Page App containing a Data Presenter, Upload Service and API Caller.

### Crawling Services

- Various services for crawling application like [Google Maps](https://www.google.ro/maps), [Waze](https://www.waze.com/), Road Sign DB with the purpose of gathering informations regarding user routes or traffic signs.

### MongoBD Database

- A database for storing traffic sign informations compiled from the users.

## External Links:

- [Trello Dashboard](https://trello.com/invite/b/oqQVx86H/6f1d0bb669434c1de98e154e15b24a16/wade-project-trasd)
- [OpenAPI Specification - Swagger](https://app.swaggerhub.com/apis/cristi.rusu/TRASD-WADe-Project/1.0.0#)
