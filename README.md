# Spices&Herbs Restaurant Website

This is a full-stack restaurant website developed using HTML, CSS, JavaScript, React.js (with Axios and Redux) for the frontend, and Java, Spring Boot, and MySQL for the backend.

## Introduction

The Spices&Herbs website provides a platform for customers to browse the restaurant menu, place orders, and make payments online. It includes user authentication, a menu catalog, order placement, and a secure payment gateway powered by Cashfree.

## Features

- User Authentication (Login/Signup)
- Browse Menu
- Place Orders
- Make Payments (powered by Cashfree)
- Order History
- Global State Management with Redux


## Deployment

- Frontend: Deployed on Vercel
- Backend: Deployed on Railway


## Technologies Used

### Frontend

- HTML
- CSS
- JavaScript
- React.js (Axios for API calls)
- Redux

### Backend

- Java
- Spring Boot
- MySQL

## Installation

### Prerequisites

- Node.js
- npm
- Java (JDK 17)
- MySQL

### Frontend Setup

1. Install the dependencies:

    
sh
    npm install


2. Start the frontend development server:

    
sh
    npm start


### Backend Setup

1. Clone the repository:

    
sh
    git clone https://github.com/YourUsername/SpicesHerbsBackend.git
    cd SpicesHerbsBackend


2. Set up MySQL database:

    
sql
    CREATE DATABASE spicesherbs_db;


3. Update application.properties file with your MySQL credentials:

    
properties
    spring.datasource.url=jdbc:mysql://localhost:3306/spicesherbs_db
    spring.datasource.username=YOUR_DB_USERNAME
    spring.datasource.password=YOUR_DB_PASSWORD
    spring.jpa.hibernate.ddl-auto=update


4. Build and run the backend:

    
sh
    cd backend
    mvn clean package
    java -jar target/SpicesHerbsBackend-0.0.1-SNAPSHOT.jar


The application should now be running with the frontend accessible at http://localhost:3000 and the backend accessible at http://localhost:8080.

## Usage

1. Register a new user or log in with existing credentials.
2. Browse the menu and select items to order.
3. Place an order and proceed to payment.
4. Make payments securely through Cashfree.
5. View your order history.

