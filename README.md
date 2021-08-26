# api-gateway

This repo is used to learn microservice together with other modules
* service-registry 
* department-service (in the UserService use DEPARTMENT-SERVICE in the URL)
* user-service
* api-gateway
* circuit breaker
* cloud-config-server
* zipkin/sleuth dependency
* zipkin server: tracing log betweeen microservices https://zipkin.io/pages/quickstart.html

### Video: https://www.youtube.com/watch?v=BnknNTN8icw

  1. set up euerka client in cloud-gateway project
	2. set up gateway/routes/pd/uri/predicates for each micro services
  3. then all the service can be access in the new port thru the new api-gateway:9191 

