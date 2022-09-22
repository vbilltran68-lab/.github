# Annio Microservice
Build a microservice system, which supports for any ecommerce product.

## Background
This project is used for testing with microservices approach.

## Microservice Patterns Roadmap
![Microservice patterns roadmap](https://microservices.io/i/MicroservicePatternLanguage.jpg)

## Todo

#### Data management
- [ ] Use Pattern: [Database per service](https://microservices.io/patterns/data/database-per-service.html)
- [ ] Use Pattern: [Saga](https://microservices.io/patterns/data/saga.html)
- [ ] Use Pattern: [Event sourcing](https://microservices.io/patterns/data/event-sourcing.html)

#### Transactional messaging
- [ ] Use Pattern: [Transactional Outbox](https://microservices.io/patterns/data/transactional-outbox.html)
- [ ] Use Pattern: [Transaction log tailing](https://microservices.io/patterns/data/transaction-log-tailing.html)
- [ ] Use Pattern: [Polling publisher](https://microservices.io/patterns/data/polling-publisher.html)

#### Testing
- [ ] Use Pattern: [Service component test](https://microservices.io/patterns/testing/service-component-test.html)
- [ ] Use Pattern: [Service integration contract test](https://microservices.io/patterns/testing/service-integration-contract-test.html)

#### Deployment
- [ ] Use Pattern: [Multiple services per host](https://microservices.io/patterns/deployment/multiple-services-per-host.html)
- [ ] Use Pattern: [Single service instance per host](https://microservices.io/patterns/deployment/single-service-per-host.html)
- [ ] Use Pattern: [Service instance per VM](https://microservices.io/patterns/deployment/service-per-vm.html)
- [ ] Use Pattern: [Service instance per container](https://microservices.io/patterns/deployment/service-per-container.html)
- [ ] Use Pattern: [Serverless deployment](https://microservices.io/patterns/deployment/serverless-deployment.html)
- [ ] Use Pattern: [Service deployment platform](https://microservices.io/patterns/deployment/service-deployment-platform.html)

#### Cross cutting concerns
- [ ] Use Pattern: [Microservice chassis](https://microservices.io/patterns/microservice-chassis.html)
- [ ] Use Pattern: [Service template](https://microservices.io/patterns/service-template.html)
- [ ] Use Pattern: [Externnalize configuration](https://microservices.io/patterns/externalized-configuration.html)

#### Communication style
- [ ] Use Pattern: [Remote Procedure Invocation (RPI)](https://microservices.io/patterns/communication-style/rpi.html)
- [ ] Use Pattern: [Messaging](https://microservices.io/patterns/communication-style/messaging.html)
- [ ] Use Pattern: [Domain-specific protocol](https://microservices.io/patterns/communication-style/domain-specific.html)
- [ ] Use Pattern: [Idempotent Consumer](https://microservices.io/patterns/communication-style/idempotent-consumer.html)
- [ ] Use gRPC: [gRPC](https://grpc.io/)

#### Observability
- [ ] Use Pattern: [Log aggregation](https://microservices.io/patterns/observability/application-logging.html)


## Architecture
![Annio Flow](https://github.com/annio-lab/annio-starter/raw/master/assets/annio-microservice-flow.png)

### Deployment
Using Heroku Cloud

### Demo
- link: https://annio-shop.herokuapp.com/
