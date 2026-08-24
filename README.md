# Campus Store — E-commerce Platform

Full-stack e-commerce web application developed with **Java, C#, REST Web Services and MySQL**, integrating a distributed architecture, business logic, database management, reporting and cloud deployment.

## Overview

**Campus Store** is a web-based e-commerce and administrative management system developed as an academic project at PUCP.

The system was designed using a **distributed and layered architecture**, separating the presentation layer from business logic and data persistence.

The application integrates a **Java backend** exposed through REST Web Services with a **C# frontend**, supported by a relational database and cloud infrastructure.

The platform includes customer-facing purchasing functionality as well as administrative tools for managing users, products, orders, inventory and reports.

---

## Architecture

The application follows a distributed and layered architecture:

```text
┌──────────────────────────────┐
│       C# Frontend            │
│      ASP.NET Web Forms       │
└──────────────┬───────────────┘
               │
               │ REST Web Services
               ▼
┌──────────────────────────────┐
│        Java Backend          │
│     Business Logic + API     │
│          GlassFish           │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│            MySQL             │
│       Data Persistence       │
└──────────────────────────────┘

              AWS
        ┌───────────────┐
        │ Cloud Database │
        │ Virtual Machine│
        └───────────────┘
```
The frontend communicates with the backend through REST Web Services, while the backend handles business logic, data access and interaction with the database.

The application was also deployed using AWS infrastructure, including a cloud database and a virtual machine for application deployment.

## My Contribution

I worked as a Full-Stack Developer within the project.

**My main responsibilities included:**

- Development of the administration module.
- Implementation of backend functionality and business logic.
- Development and integration of REST Web Services.
- Integration between the C# frontend and Java backend.
- Support for customer-facing functionality.
- Support for product and order management.
- Work with database access and persistence components.
- Integration and deployment of the application using AWS infrastructure.

I also participated in the integration and testing of the different components of the system.

## Key Features
- Customer Module
- Product catalog.
- Product search and filtering.
- Search by title, author, genre and publisher.
- Product and stock information.
- Order creation and management.
- Payment status tracking.
- WhatsApp-based payment coordination.
- QR code integration.
- Automatic order cancellation according to business rules.
- Administration Module
- User management.
- Product management.
- Order management.
- Inventory management.
- Best Sellers reports.
- Sales reports.
- Revenue, discounts and net income information.
- Business Rules

The system implements several business rules related to orders, payments and inventory.

Stock Management

When an order is created, the system reserves virtual stock for the requested products.

Payment Deadline

Orders that remain pending payment are automatically cancelled after 48 hours if the payment is not completed.

Uncollected Orders

If an order is not collected within 7 business days, the system processes the corresponding restocking and refund rules.

Refund and Penalty

For applicable uncollected orders, the system applies a 20% penalty according to the defined business rules.

## Technologies
#### Backend
- Java
- GlassFish
- REST Web Services
#### Frontend
- C#
- ASP.NET Web Forms
**Database**
- MySQL
#### Cloud / Deployment
- AWS
- Cloud database infrastructure
- Virtual machine for application deployment
#### Reporting
- Jasper Reports
#### Other Integrations
- External image service
- QR codes
- WhatsApp links
## Project Structure

The project separates responsibilities into different components, including:

DTO — Data Transfer Objects.
Business Logic — Application and business rules.
DB Manager — Database access and persistence.
Encryption — Data protection and encryption-related functionality.
REST — REST Web Services used for communication between application components.
Frontend — C# / ASP.NET Web Forms application.
Technical Highlights
Full-stack development using Java and C#.
Distributed application architecture.
Layered separation of responsibilities.
RESTful Web Services.
Relational database design using MySQL.
Business logic for orders, payments and inventory.
User and product management.
Automated business rules for order processing.
Report generation using Jasper Reports.
Cloud deployment using AWS infrastructure.
Integration between multiple application components and external services.
Skills Demonstrated

This project allowed me to apply and strengthen skills in:

Full-Stack Development
Backend Development
REST API Development
Distributed Systems
Relational Databases
Business Logic
Software Architecture
Cloud Deployment
Database Management
Web Application Development
Problem Solving
Team Collaboration
Academic Context

Developed as part of the Programming 3 course at Pontificia Universidad Católica del Perú (PUCP).

The project focused on applying concepts related to:

Object-Oriented Programming
Layered Architecture
Distributed Applications
Web Services
Database Management
Full-Stack Development
Business Logic Implementation
Cloud Deployment

