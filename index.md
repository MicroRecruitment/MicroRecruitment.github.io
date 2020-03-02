# Micro Recruitment
This project is a result of the work in the course IV1201 Architecture and Design of global applications at KTH from the start of 2020. 

The task was to create a web application to serve as a reqruitment platform, but only implement as much functionality to fulfill certain tasks. Thus this application is more of a skeletion then anything else.

The code is based on Node.js and contains three micro services. The services are using internal comunication via RabbitMQ queues and storing information in a DB2 database. The services are prepared to run in OpenShift for scalability and reliability.

## Micro services
### [GateKeeper](/GateKeeper)
The GateKeeper service conatins the client code aswell as a gateway to handle client requests.

### [Auth](/Auth)
The Auth service provides backend support for registering, logging in and validating users.

### [Applicants](/Applicants)
The Applicats service provides backend support for applying for jobs and handeling applications.
