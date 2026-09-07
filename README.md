# Spring Microservice Handbook

## Arquitetura Microservices
- Evolução Arquitetural
- Modelagem de Arquiteturas Distribuídas
- **Microservices de Negócios**
  - Divisão do Negócio
    - Business Capabilities
    - Subdomain DDD
  - Granularidade dos Serviços
  - Desacoplamento em Microservices
- **Modelagem de Bases de Dados em Microservices**
  - Padrão Base de Dados Compartilhada
  - Padrão Base de Dados por Microservice
- **Cross Cutting Concerns**
  - Microservices de Configurações
    - Config Server
    - API Gateway
    - Service Registry
  - Observabilidade em Microservices
  - Autenticação e Autorização em Microservices
    - Autenticação e Autorização no Gateway
    - Autenticação e Autorização com Access Token

## Microservices Patterns
- Ports and Adapters Pattern
- **Message**
  - Broker Pattern
  - Mediator Pattern
- **Event Driven**
  - Event Notification Pattern
  - Event Carried State Transfer Pattern
- **Saga Pattern**
  - Orquestração
  - Coreografia
- **API Composition Pattern**
  - Gateway
  - Agregator
- API Gateway Pattern
- Registry Discovery Pattern
- Global Configuration Pattern
- **Observability**
  - Metrics Pattern
  - Distributed Tracing Pattern
  - Log Aggregation Pattern
- Circuit Breaker Pattern

## Comunicações entre Microservices
- Comunicação Síncrona
- Comunicação Assíncrona
- Via APIs
- Via Mensageria
- Mensageria via Comandos
- Mensageria via Eventos
- Transferência de Estado
- Por Base de Dados

## Gestão dos Dados Distribuídos
- Teorema CAP
- Consistência Eventual
- Disponibilidade em Microservices
- Replicação de Dados
- Sincronia de Dados Distribuídos
- Transação Distribuída
- Identificadores Distribuídos

## Ecossitema Spring
- Spring Framework
- **Spring Boot**
  - Automatic Run, Configurations and Dependencies
  - Embedded Application Server
- **Spring Web**
  - Validation
  - API RESTful
- Spring HATEOAS
- **Spring Cloud**
  - Gateway
  - Circuit Breaker
  - Resilience4J
  - Eureka
  - Config
  - Observability
- **Spring Data**
  - **JPA**
    - Pagination
    - Repositories
    - JPA Criteria Builder
    - @Query
    - Filters
  - MongoDB
  - Redis
  - Elasticsearch
- Spring AMQP
- Spring Actuator
- **Spring Security**
  - **Authentication**
    - Basic Authentication
    - Token Authentication
      - JWT
      - Encrypted Token
      - Opaque Token
      - Refresh Token
  - **Authorization**
    - Roles
    - Permissions
