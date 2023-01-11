# microservicescore

Microservices

For Eureka Server-
server.port=8761
spring.application.name=ServiceRegistry
eureka.client.register-with-eureka= false
eureka.client.fetch-registry= false

Hystrix Status->
http://localhost:2023/actuator/hystrix.stream

http://localhost:9195/hystrix

API Gateway
spring.main.allow-circular-references: true
