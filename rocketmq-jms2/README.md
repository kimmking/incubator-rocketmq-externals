# RocketMQ-JMS2
RocketMQ JMS 2.0.

## Introduction
RocketMQ-JMS2 is an implement of JMS 2.0 specification,taking Apache RocketMQ as broker.
Now we are on the way of supporting JMS2.0 is our final target.   


## Building

  > cd rocketmq-jms2
  > mvn clean install  
  
  **run unit test:**  
  > mvn test    
  
  **run integration test:**  
  > mvn verify
  
  **see jacoco code coverage report**
  > open core/target/site/jacoco/index.html  
  > open core/target/site/jacoco-it/index.html  
  > open spring/target/site/jacoco-it/index.html 
  
  
## Guidelines

 Please see [Coding Guidelines Introduction](http://rocketmq.apache.org/docs/code-guidelines/)
