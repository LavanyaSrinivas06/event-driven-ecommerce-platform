

# Event-Driven E-Commerce Order Processing Platform

This project simulates how a real-world e-commerce backend processes orders using **microservices and event-driven architecture**.

The goal of this project is to demonstrate production-level backend engineering concepts including service boundaries, asynchronous messaging, idempotent APIs, and distributed system reliability patterns.

## Architecture Overview

The platform consists of multiple microservices communicating through **Apache Kafka** events.

Services include:

- API Gateway
- Order Service
- Inventory Service
- Payment Service
- Shipping Service
- Notification Service

Each service owns its own database and communicates using asynchronous events.

## Tech Stack

- Java 17
- Spring Boot
- Apache Kafka
- PostgreSQL
- Docker + Docker Compose
- REST APIs
- JUnit Testing

## Key Backend Engineering Concepts Demonstrated

- Microservices architecture
- Event-driven communication
- Kafka producers and consumers
- Idempotent APIs
- Distributed transaction patterns
- Retry and dead-letter queues
- Database per service
- Containerized infrastructure

## Planned Architecture

event-driven-ecommerce-platform
│
├── api-gateway
├── order-service
├── inventory-service
├── payment-service
├── shipping-service
├── notification-service
│
├── shared-kernel
├── infrastructure
├── docs
└── scripts
