                                                  gateway_service
1)About the project.     

This project is a gateway microservice that is needed for other services. Requests to other services pass through the gateway.

Also, in this project, the config client is used to receive file configurations, as well as the eureka client

2)Start the project locally.

2.1 Required to install the project.

Java 11

2.2 How to run project.

You should create environmental variables that are defined in the resources package like:

application.properties.

2.2.1 For application.properties you should set the value like:

* spring.cloud.config.uri=${Value}
* spring.application.name=${Value}
* spring.cloud.gateway.discovery.locator.enabled=${Value}
* server.port=${Value}
