# JPMorgan Chase Midas Forage Simulation

## Overview
Completed the JPMorgan Chase Software Engineering Virtual Experience Program on Forage.

## Technologies Used
- Java 17
- Spring Boot
- Apache Kafka
- JPA / Hibernate
- H2 Database
- Maven
- REST APIs

## Features Implemented
- Kafka transaction consumer
- Transaction validation
- Database persistence using JPA
- Incentive API integration
- Balance REST API
- User balance management

## Skills Demonstrated
- Backend Development
- Event-Driven Architecture
- REST API Integration
- Database Design
- Spring Boot Development

# Midas Banking System

A Spring Boot based banking transaction processing system built as part of the JPMorgan Chase Software Engineering Virtual Experience.

## Architecture

Kafka Producer
      ↓
Kafka Consumer
      ↓
Transaction Validation
      ↓
H2 Database
      ↓
Incentive API
      ↓
Balance REST API



Kafka
  ↓
Transaction Listener
  ↓
Validation Layer
  ↓
JPA Repository
  ↓
H2 Database



Incentive API
      ↑
 REST Call
