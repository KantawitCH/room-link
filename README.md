# **RoomLink**

## **Project Overview**

This project is a full-stack web application designed as a booking platform for users to:

- Search properties using various filters.
- View detailed property information.
- Make bookings with availability checks.
- Process payments through mock or real gateways.

---

## **Objectives**

#### **Primary Objective**

Build a scalable web application that provides core booking functionality, including property search, booking management, and payment processing.

#### **Personal Development Objectives**

- Gain hands-on experience with:
    - **Backend**: Spring Boot for RESTful APIs and business logic.
    - **Frontend**: React for interactive user interfaces.
    - **Search**: Elasticsearch for efficient and fast search capabilities.
    - **Database**: PostgreSQL for relational data storage.
- Design and implement scalable system and database architectures.
- Solve real-world challenges like search optimization, API integration, and deployment.

---

## **Scope**

### **Core Features**

- User authentication (sign-up, login, logout).
- Property search with filters (location, price, ratings).
- Property details page with images, descriptions, pricing, and reviews.
- Booking system with availability checks and confirmation.
- Payment processing (mock implementation or real gateway integration).

### **Out of Scope (Initial Phase)**

- Multi-language support.
- Advanced features like dynamic pricing and promotions.

---

## **How to Run the Project**

1. **Clone the repository**:
    
    ```
    git clone https://github.com/yourusername/booking-platform.git cd room-link
    ```
    
2. **Set up the backend**:
    
    - Install dependencies.
    - Configure database settings in `application.yml`.
    - Start the Spring Boot server.
3. **Set up the frontend**:
    
    - Navigate to the frontend folder.
    - Install dependencies:
        
        ```
        npm install
        ```
        
    - Start the React app:
        
        ```
        npm start
        ```
4. **Start Elasticsearch**:
    
    - Make sure Elasticsearch is running locally or via Docker.
5. **Run the application**:
    
    - Open ```http://localhost:3000``` in your browser to access the application.
---

## **Functional Requirements**

> _Note: These are subject to change as development progresses._

- **User Authentication**: Secure sign-up, login, and logout functionalities using hashed passwords.
- **Property Search**: Full-text search using Elasticsearch with filters for price range, location, and ratings.
- **Booking System**: Enable date-based bookings with double-booking prevention.
- **Admin Panel**: Tools for managing properties, bookings, and user accounts.
- **Payment**: Mock payment processing or integration with gateways like Stripe/PayPal.

---

## **Non-Functional Requirements**

> _Note: These are subject to change as development progresses._

- **Performance**: Search results load within 2 seconds; supports up to 100 users initially.
- **Scalability**: Design supports future scaling for 1,000+ users.
- **Security**: Implement JWT for session management; secure APIs to prevent SQL injection and XSS.

---

## **Milestones**

1. **Setup**: Initialize backend, frontend, and database environments.
2. **Core Features**:
    - User authentication.
    - Search functionality with Elasticsearch and PostgreSQL.
3. **Booking System**: Implement booking logic with date availability checks.
4. **Payment Integration**: Add mock payment or integrate a real payment gateway.
5. **Admin Panel**: Build tools to manage properties and bookings.
6. **Deployment**: Dockerize and deploy the application to a cloud platform.

---

## **Mock Data**

- **Users**: Predefined users with basic profile information.
- **Properties**: Sample properties with attributes like name, location, price, and images.
- **Bookings**: Example booking records for testing and demonstration purposes.

---

## **Technologies Used**

- **Frontend**: React
- **Backend**: Spring Boot
- **Search**: Elasticsearch
- **Database**: PostgreSQL
- **Containerization**: Docker
- **Others**: To be added as the project evolves.

---

## **Contributing**

Contributions are welcome! Feel free to submit issues or pull requests for suggestions, improvements, or bug fixes.
