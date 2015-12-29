# Web Engineering 2015-2016 / Microservices

#1.- The two microservices are running and registered.
![Alt text](https://github.com/guillepg/Laboratory-6-microservices/tree/master/img/1_1.PNG)
![Alt text](https://github.com/guillepg/Laboratory-6-microservices/tree/master/img/1_2.PNG)
#2.- The service registration service has the two microservices registered.
![Alt text](https://github.com/guillepg/Laboratory-6-microservices/tree/master/img/2_1.PNG)
![Alt text](https://github.com/guillepg/Laboratory-6-microservices/tree/master/img/2_2.PNG)
#3.- A second account microservice is running in the port 4444 and it is registered.
![Alt text](https://github.com/guillepg/Laboratory-6-microservices/tree/master/img/3_1.PNG)
#4.- A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?
Yes, because the secondary accounts-service is registered with the same name as the one that is now unavailable and retrieves the information from port 4444