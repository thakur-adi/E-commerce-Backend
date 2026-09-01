---

# E-commerce-Backend
```text
A centralized repository for the E-commerce Backend ecosystem, providing an overview, documentation, and links to the individual microservices that collectively power the platform. The project follows a distributed microservice architecture where each service owns a specific business capability and communicates with other services through well-defined APIs and asynchronous messaging where appropriate.
```
---

## Product-Catalogue MicroService
```
A backend-focused Product-Catalog microservice built with Spring Boot, featuring public product browsing and paginated search, role-based authorization for product management, and secure service-to-service authentication through the User-Auth Service.
```
HTTPS:- https://github.com/thakur-adi/product-catalog-service.git

SSH:- [git@github.com](mailto:git@github.com):thakur-adi/product-catalog-service.git

---

## User-Authentication MicroService
```
A backend-focused User Management and Authentication microservice built with Spring Boot and Spring Security, featuring JWT authentication, stateful refresh token management with rotation, token revocation, secure session lifecycle management, and clean, maintainable architecture.
```
HTTPS:- https://github.com/thakur-adi/user-auth-service.git

SSH:- [git@github.com](mailto:git@github.com):thakur-adi/user-auth-service.git

---

## Email MicroService
```
Lightweight Kafka-driven email microservice — consumes topic-per-action events from the User-Auth-Service and dispatches emails via SMTP, with the payload fully owned by the producer.
```
HTTPS:- https://github.com/thakur-adi/Email-Service.git

SSH:- [git@github.com](mailto:git@github.com):thakur-adi/Email-Service.git

---

## Payment MicroService
```
A backend-focused Payment microservice built with Spring Boot, implementing secure payment processing with Stripe and Razorpay, Checkout Session integration, webhook-based transaction persistence, extensible multi-gateway support via Strategy, Adapter, and Factory patterns, and a scalable architecture designed for distributed e-commerce systems.
```
HTTPS:- https://github.com/thakur-adi/payment-service.git

SSH:- [git@github.com](mailto:git@github.com):thakur-adi/payment-service.git

---

## Order MicroService
```
A backend-focused Order Management microservice built with Spring Boot, featuring authenticated order creation, paginated order history, order status tracking and payment integration. It orchestrates checkout between the Cart and Payment Services while maintaining the order and payment lifecycle through secure service-to-service communication.
```
HTTPS:- https://github.com/thakur-adi/order-service.git

SSH:- [git@github.com](mailto:git@github.com):thakur-adi/order-service.git

---

## Cart MicroService
```
A backend-focused Cart microservice built with Spring Boot, featuring authenticated cart management, user-specific cart ownership, quantity-aware cart operations, cart lifecycle management, and checkout integration with the Order Service through clean service-to-service communication.
```
HTTPS:- https://github.com/thakur-adi/cart-service.git

SSH:- [git@github.com](mailto:git@github.com):thakur-adi/cart-service.git

---

## Service Discovery
```
A backend-focused Service Discovery server built with Spring Boot and Netflix Eureka, providing centralized service registration and discovery for the E-Commerce microservices architecture. It enables dynamic service-to-service communication and client-side load balancing through Eureka-based discovery and load-balanced RestTemplate.
```
HTTPS:- https://github.com/thakur-adi/service-discovery.git

SSH:- [git@github.com](mailto:git@github.com):thakur-adi/service-discovery.git

---
