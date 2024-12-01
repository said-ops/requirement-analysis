# Requirement Analysis in Software Development
This repository is for the requirment analysis of the Airbnb clone project we'll be building, this study is necessairy because it helps highlighting the non coding-related aspects while building a large application

## What is Requirement Analysis?
Requirement Analysis is a crucial phase of Software Development Lifecyle, where the project team gathers, analyses and defines the the requirment of the product to be developed.

## Why is Requirement Analysis Important?
- Clarity and Understanding: It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- Scope Definition: Clearly defines the scope of the project, which helps in preventing scope creep.
- Basis for Design and Development: Provides a solid foundation for designing and developing the system.

## Key Activities in Requirement Analysis.
1. Requirement Gathering
- Engage with stakeholders to collect initial requirements.
- Use various techniques like interviews, surveys, and workshops.
2. Requirement Elicitation
- Refine and elaborate on the gathered requirements.
- Use techniques like brainstorming, focus groups, and prototyping.
3. Requirement Documentation
- Document the requirements in a detailed and structured format.
- Use requirement specification documents, user stories, and use cases.
4. Requirement Analysis and Modeling
- Analyze and prioritize the requirements.
- Create models to visualize and understand the requirements.
5. Requirement Validation
- Review and validate the requirements with stakeholders.
- Define acceptance criteria and ensure traceability.

## Types of Requirements.
### Functional Requirements

**Definition**: Describe what the system should do.
**Examples**: User authentication, property search, booking system, user registration.

**Key Functional Requirements**:

**Search Properties**: Users should be able to search for properties based on various criteria such as location, price, and availability.
**User Registration**: New users should be able to create an account with personal details and login credentials.
**Property Listings**: Display properties with essential details and images.
**Booking System**: Users should be able to book properties, view booking details, and manage their bookings.
**User Authentication**: Secure login and registration process for users.

### Non-functional Requirements

**Definition**: Describe how the system should perform.
**Examples**: Performance, security, scalability, usability, reliability.

**Key Non-functional Requirements**:

**Performance**: The system should load pages within 2 seconds and handle up to 1000 concurrent users.
**Security**: Ensure data encryption, secure login, and protect against common vulnerabilities.
**Scalability**: The system should be able to scale horizontally to handle increased traffic.
**Usability**: The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
**Reliability**: The system should have an uptime of 99.9% and recover quickly from any failures.

## Use Case Diagrams.

**Objective**: Visual representation of interactions between users and the system.

**What are Use Case Diagrams?**

Use case diagrams show how different users (actors) interact with the system to achieve specific goals (use cases).
**Creating Use Case Diagrams:**

1. Identify actors (e.g., guest, registered user, admin).
2. Define use cases (e.g., search properties, book property, manage listings).
3. Draw interactions between actors and use cases.
**Benefits of Use Case Diagrams**:

- Provide a clear visual representation of system functionalities.
- Help in identifying and organizing system requirements.
- Facilitate communication among stakeholders and development team.

![Use Case Diagram](alx-booking-uc.png)  

## Acceptance Criteria.

Acceptance Criteria define the conditions that a feature or system must meet to be accepted by stakeholders.

**Importance**:
- Provides a clear definition of done.
- Reduces ambiguity and misunderstandings.
- Ensures alignment with stakeholder expectations.
**Example for Checkout Feature**:
- The user can view a summary of their booking details.
- The user can enter payment information and complete the booking.
- The system sends a confirmation email upon successful checkout.
- Errors or incomplete information display appropriate error messages.

