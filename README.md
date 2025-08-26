# Bank of Checkmarx - Core Banking Backend

A Java Spring Boot-based core banking service for the Bank of Checkmarx demo application with intentionally vulnerable endpoints. This service handles account management, transaction processing, customer data, and provides foundational banking business logic for the financial platform.

## Security Note

⚠️ **This is an intentionally vulnerable application for security testing purposes. Do not deploy in production or sensitive environments.**

## Overview

The Core Banking Backend is a Spring Boot application that provides essential banking business logic including account management, transaction processing, and data persistence. It integrates with PostgreSQL for data storage and features comprehensive security policies and audit logging.

## Key Features

- **Account Management**: Customer account creation and lifecycle management
- **Transaction Processing**: Real-time transaction processing and validation
- **Data Persistence**: PostgreSQL database integration with JPA/Hibernate
- **Authentication Services**: JWT-based authentication with role-based access control
- **Business Logic**: Core banking rules and policy enforcement
- **REST API**: RESTful endpoints for banking operations
- **Security Framework**: Spring Security integration
- **Audit Logging**: Comprehensive security and compliance logging
- **Health Monitoring**: Spring Actuator health checks and metrics
- **Structured Logging**: Logback-based logging with JSON formatting

## Technology Stack

- **Java 11**: Programming language
- **Spring Boot 2.7.0**: Application framework
- **Spring Security**: Authentication and authorization
- **Spring Data JPA**: Database access layer
- **PostgreSQL**: Primary database storage
- **Hibernate**: Object-relational mapping
- **Jackson 2.13.3**: JSON serialization/deserialization
- **XStream 1.4.13**: XML processing
- **JJWT 1.3.3**: JWT token handling
- **Logback**: Structured logging framework
