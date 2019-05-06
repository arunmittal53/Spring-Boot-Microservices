# Spring-Boot-Microservices

Contains 3 microservices
  * Movie-catalog-service
  * Movie-info-service
  * Rating-data-service
 
 Communicate with each other via **RestTemplate** using **Server Discovery**.
 
 Connect these services using **Eureka server** by making above microservices **Eureka Clients** by adding them to class paths.
 
 Use **LoadBalanced** annotation with REST Template on Client side 
 
  ![Code Structure](https://github.com/arunmittal53/Spring-Boot-Microservices/blob/master/Spring%20Boot%20Microservices.jpeg)
