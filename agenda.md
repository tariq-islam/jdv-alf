1. Introduction - RB
1. Shared Data Services - RB
1. Work being done on CDC and Kafka - RB
1. Data as a Service - APIs and DV - RB
1. Current State - Tariq
    * Infrastructure - Cost
    * Traditional ETL
    * Web Services 
1. What the Mission Needs:     
    * Microservice Enablement  - data schema ownership and CI/CD integration    
        * DBA vs Devs conflicting priorities
        * Abstract Data Ownership 
        * Transactional Boundries - **can you talk about MS transactions in a bit more detail?
        https://www.slideshare.net/chris.e.richardson/solving-distributed-data-management-problems-in-a-microservice-architecture-sfmicroservices?ref=http://microservices.io/microservices/news/2017/08/01/data-patterns-presentation.html
        Can DV help with slides 46-48?
    * Federation / Real time view of data    
    * Data Migrations and Modernization (from proprietary, mainframe abstraction)    
    * Real Time Analytics and Business Intelligence
1. Setting a baseline - What is JDV
    * Abstraction Layer 
    * Virtualized Data Access <- common access point to different sources (vs copy data management)
    * Transformation <- where and how?
    * Data Federation <- performance?
    * Data Delivery <- Latency/Cost?
1. Benefits of DV
    * no replication, realtime view, writeback functionality
    * Reducing Latency and Cost
    * Improving Security (role based access)
    * Performance
1. Let's build something
6. Architectural Overview of JDV
8. Quesitons
