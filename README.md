Some times we need trigger a message via rabbitMQ to validate the event handlers logic. 
This repo uses a plugin "AMQP plugin for Jmeter" to simulate the common rabbitMQ different modes. 

 Rabbit Common usage mode
 http://www.rabbitmq.com/getstarted.html

 AMQP Plugin for JMeter
 https://github.com/jlavallee/JMeter-Rabbit-AMQP
 

Before launch Jmeter, need place the 2 jars in the jmeter ext/lib folder:
amqp-client-4.1.0.jar
JmeterAMQP.jar ( build from the AMQP Plugin repo)

After launching the Jmeter, there are 2 new types of samplers: AMQP Consumer and AMQP Publisher.
