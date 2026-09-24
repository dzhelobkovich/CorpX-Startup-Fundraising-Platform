# CorpX — Startup & Fundraising Platform

CorpX is a microservices-based platform for startup management and fundraising.

The project was developed by a team of five developers during a practical Java Backend Development Bootcamp, with regular code reviews and guidance from experienced Java developers and Tech Leads.

This repository provides an overview of the project, its architecture, and my contributions. The source code is available in the linked service repositories.

## My Contributions

### URL Shortener Service

Participated in the design and development of a microservice for generating and managing short links used in the referral system.

Repository: [url_shortener_service](https://github.com/dzhelobkovich/url_shortener_service)

### Notification Service

Designed and developed notification functionality for Email, SMS, and messenger notifications. Apache Kafka was used for asynchronous communication and event processing.

Repository: [notification_service](https://github.com/dzhelobkovich/notification_service)

### News Feed

Contributed to the development of an event-driven News Feed using Apache Kafka for asynchronous event processing and Redis for caching.

Repository: [post_service](https://github.com/dzhelobkovich/post_service)

### Other Contributions

- Implemented Redis caching to reduce database load and improve request processing.
- Implemented upload, compression, and storage of images, video, and audio using MinIO and Amazon S3 API.
- Implemented scheduled cleanup of outdated data using Spring Scheduler.
- Wrote unit and integration tests using JUnit 5, MockMvc, and Testcontainers.
- Set up automated test execution with GitHub Actions.
- Worked with Swagger/OpenAPI for REST API documentation.
- Participated in code reviews and Scrum-based team development.

## Architecture

CorpX is built using a microservices architecture. Individual services are responsible for separate business domains and communicate through REST APIs and asynchronous events using Apache Kafka.

| Service | Responsibility | Repository |
| --- | --- | --- |
| URL Shortener Service | Short and referral link management | [url_shortener_service](https://github.com/dzhelobkovich/url_shortener_service) |
| Account Service | Account-related functionality | [account_service](https://github.com/dzhelobkovich/account_service) |
| Project Service | Startup and project management | [project_service](https://github.com/dzhelobkovich/project_service) |
| Post Service | Posts and News Feed functionality | [post_service](https://github.com/dzhelobkovich/post_service) |
| User Service | User management | [user_service](https://github.com/dzhelobkovich/user_service) |
| Payment Service | Payment-related functionality | [payment_service](https://github.com/dzhelobkovich/payment_service) |
| Notification Service | Email, SMS, and messenger notifications | [notification_service](https://github.com/dzhelobkovich/notification_service) |
| Analytics Service | Analytics and metrics processing | [analytics_service](https://github.com/dzhelobkovich/analytics_service) |
| Achievement Service | Achievement-related functionality | [achievement_service](https://github.com/dzhelobkovich/achievement_service) |
| Infrastructure | Infrastructure and environment configuration | [infra](https://github.com/dzhelobkovich/infra) |

The repositories above are forks of the original repositories from the [CorporationX](https://github.com/CorporationX) organization and contain the codebase used during the team project.

## Tech Stack

**Backend:** Java 17, Spring Boot 3, Spring Data JPA, Hibernate, REST API

**Data:** PostgreSQL, Redis

**Messaging:** Apache Kafka

**Storage:** MinIO, Amazon S3 API

**Testing:** JUnit 5, MockMvc, Testcontainers

**Tools:** Docker, Git, GitHub Actions, Swagger/OpenAPI, Jira

**Development practices:** Microservices, Event-Driven Architecture, Unit Testing, Integration Testing, CI, Code Review, Scrum

## Links

[GitHub Profile](https://github.com/dzhelobkovich)  
[CorporationX Organization](https://github.com/CorporationX)
