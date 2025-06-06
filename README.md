# AirBnB Clone Project

Project to polish up backend coding and DevOps skills 
4th May 2025

## Introduction

The AirBnB clone project will help me polish up my backend dev skills

## Technologies

- **Django** - a high-level Python web framework that promotes simple, straightforward design and quick development. 
- **MySQL** - an open source relational database management system (RDBMS).
- **GraphQL** - an API query language and runtime that uses your current data to fulfill queries.
- **Docker** - Docker is an open source platform that helps developers build, deploy, execute, update and manage containerized apps.
- **GitHub Actions** - a continuous integration/continuous delivery platform to help automate your build, test, and deployment process.

## Team Roles

- **Business Analyst (BA)**- converts the business needs of customers into specifications.  
- **Product owner (PO)** - is in charge of the product's development and vision.
- **Project Manager (PM)** - ensures timely and cost-effective delivery of a product or its components.
- **UI/UX designer** - converts a product's concept into designs that are easy to utilize.
- **Software Architect** - chooses the right platforms and tools to carry out the product concept.
- **Software Developer** - resolves any technical issues that may arise throughout the development process.
- **Quality assurance(QA) engineer** - verifies that an application operates in accordance with the specifications
- **Test automation engineer** - creates and manages automated testing test scripts.
- **DevOps engineer** - creates pipelines for continuous integration and continuous delivery (CI/CD) to expedite delivery.
    
## Database Design

- **Key entities**: Users, Properties, Bookings, Reviews and Payments.

#### Users
**Fields**: Name, password, email

#### Properties
**Fields**: Name, location, availability, facilities, price per night, images

#### Bookings
**Fields**: Check in and check out dates, number of guests, guest demographic [adults, children, infants, pets]

#### Reviews
**Fields**: Text, name, star ratings

#### Payments
**Fields**: Payment options, total cost, cost per night

## Features
**Main features**
_- Guests booking_ - guests should be able to book a property for the number of nights they wish to stay. They should be able to customize their booking, based on demographic (adults, children and pets)
- _Property listing_ - guests should be able to see a property's cost per night, availability, facilities and manager. Property managers can list more than one property.
- _Payment system_ - guests should be able to pay for their stay. They should be able to choose the best payment option for them.

## API Security

**Key security measures to be implemented**
- _Authentication_ - different types of users will be authenticated, for example, property managers, and guests.
- _Authorization_ - each user will have a different dashboard. Guests cannot access manager dashboards.

Security is essesntial for protecting Personally Identifiable Information (PII). Processing payments also required adherence to Payment Card Industry Data Security Standard (PCI DSS standards)

## CI/CD Pipelines

CI/CD refers to a set of predetermined processes that developers must adhere to to provide new software. CI/CD pipelines makes it simple for developers to send code into production and then roll it back if there are any problems.

Tools that could be used: GitHub Actions, Docker

### License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
