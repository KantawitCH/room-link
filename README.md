# Project Overview

#### **1. Objectives**

- **Primary Objective**:  
    Build a booking platform web application that enables users to search properties, view details, make bookings, and process payments.
    
- **Personal Development Objectives**:
    
    - Gain in-depth experience with a modern tech stack, including:
        - **Backend**: Spring Boot for building scalable, RESTful APIs and implementing business logic.
        - **Frontend**: React for creating an interactive, user-friendly interface.
        - **Search**: Elasticsearch for implementing fast, efficient search functionality.
        - **Database**: PostgreSQL for designing and managing relational data storage.
        - Explore and integrate additional technologies as the project evolves.
    - Develop skills in designing scalable system and database architectures.
    - Learn to tackle real-world challenges, including search optimization, API integration, and deployment.
#### **2. Scope**

- **Core Features**:
    
    1. User authentication (sign-up, login, logout).
    2. Property search with filters (location, price, ratings).
    3. Property details page with images, descriptions, pricing, and reviews.
    4. Booking system with availability checks and confirmation.
    5. Payment processing (mock implementation or integration with a payment gateway).
- **Out of Scope** (initial phase):
    
    - Multi-language support.
    - Advanced features like dynamic pricing and promotions.

#### **3. Functional Requirements** -- Subject to change

- **User Authentication**:  
    Secure sign-up, login, and logout functionalities with hashed passwords.
- **Property Search**:
    - Full-text search using Elasticsearch.
    - Filter results by price range, location, and ratings.
- **Booking System**:
    - Users can select dates and confirm bookings.
    - Ensure no double-booking of the same property.
- **Admin Panel**:
    - Manage properties, bookings, and user accounts.
- **Payment**:  
    Process mock payments or integrate with a real gateway (Stripe/PayPal).

#### **4. Non-Functional Requirements** -- Subject to change

- **Performance**:
    - Search results should load within 2 seconds.
    - Support up to 100 simultaneous users in the initial phase.
- **Scalability**:
    - Design for future scalability to handle 1,000+ users.
- **Security**:
    - Implement JWT for session management.
    - Secure APIs and sanitize inputs to prevent SQL injection and XSS.

#### **5. Milestones**

1. **Setup**:
    - Set up backend, frontend, and database environments.
2. **Core Features**:
    - Implement user authentication.
    - Build search functionality with Elasticsearch and PostgreSQL.
3. **Booking System**:
    - Develop booking logic and date availability checks.
4. **Payment Integration**:
    - Add mock payment system or integrate a real payment gateway.
5. **Admin Panel**:
    - Develop management tools for properties and bookings.
6. **Deployment**:
    - Dockerize the application and deploy to a cloud platform.

#### **6. Mock Data**

- **Users**: Predefined users with basic profile information.
- **Properties**: Sample properties with various attributes (name, location, price, images).
- **Bookings**: Sample booking records for testing.
