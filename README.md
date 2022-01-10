# bootify.

##Content
 1. Introduction of SpringBoot
 2. Creation of basic SpringBoot Project
 3. SpringBoot starter dependecies
 4. Play with Annotations
 5. Database connection and caches
 6. Play with Spring Profile
 7. Introduction of microservice and Spring Cloud
 8. Using Log mechanism in our application
 9. API documentation
 10. Unit Testing 
 11. deployment

### Introduction
  1. Mike Youngstrom opened a PR on 17th October 2012.

  2. PR refactored Spring framework in such a manner that
     it support for container less web application.
  3. He came with an idea, To include container inside framework itself, and bootstrap from main.
  4. Phil Webb solved this issue and in 2013 Spring boot came into existence.
  5. 1st April 2014, Spring Boot 1.0 globally available.
 
   ### Benefits: 
     1. Faster way of developing applications by reducing the boilerplate configurations.
     
     2. Because of starter pack, it simplifying builds and configuration.
     
     3. creating easily production ready soltion with actuator endpoints such as
        health, httptrace, mappings, metrics, info, configprops, and so on
     
     4. Since framework itself contains embedded container server support, By default tomcat
     
     5. auto reload changes during the development only
     
     6. we can easily run by mvn/gradle spring-boot run
