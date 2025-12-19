
LifeLog

Secure Personal Journaling & Productivity Platform

LifeLog is a full-stack web application designed to help users securely record journal entries, manage daily checklists, and track personal productivity. The platform supports role-based access control, optimized REST APIs, and scalable architecture, making it suitable for real-world, production-grade use.

The project demonstrates strong JavaScript, Node.js, and full-stack engineering practices, combined with a robust backend built using Spring Boot.

🚀 Features

Authentication & Security
	•	JWT-based authentication
	•	Secure login and registration
	•	Role-based access control (USER / ADMIN)
	•	Spring Security integration

Journaling System
	•	Create, read, update, and delete journal entries
	•	Mood and sentiment tracking
	•	Persistent data storage using MongoDB

Checklist Management
	•	Add and remove daily checklist items
	•	Real-time updates on the user dashboard

Admin Dashboard
	•	View and manage registered users
	•	Promote users to admin role
	•	Secure administrative workflows

Performance & Optimization
	•	Redis-based caching
	•	Optimized REST endpoints
	•	Efficient database queries

🧱 Tech Stack

Frontend / JavaScript
	•	React.js
	•	Node.js (runtime for tooling and builds)
	•	npm
	•	JavaScript (ES6+)
	•	REST API integration
	•	Responsive UI design

Backend
	•	Java
	•	Spring Boot
	•	Spring Security
	•	JWT Authentication

Database & Caching
	•	MongoDB
	•	Redis

🏗️ System Architecture

[ React Frontend ]
   (Node.js + npm)
        |
        | REST APIs (JWT-secured)
        v
[ Spring Boot Backend ]
        |
        |----------------------|
        |                      |
   [ MongoDB ]           [ Redis ]




🔄 Application Flow

Authentication Flow

User
 → Login / Register
 → JWT Token Issued
 → Token Stored Client-Side
 → Secure API Access

Journal Management Flow

User Dashboard
 → Create / Edit Journal Entry
 → REST API Call
 → Service Layer
 → MongoDB
 → Updated UI

Admin Role Management Flow

Admin Dashboard
 → User Action Request
 → Factory Pattern
 → Role Update
 → Database



🔧 Node.js & JavaScript Responsibilities
	•	Used Node.js as the JavaScript runtime for frontend development and build tooling
	•	Managed dependencies and scripts using npm
	•	Configured environment-based settings using Node-compatible configuration files
	•	Built reusable React components using modern ES6+ JavaScript
	•	Implemented asynchronous API communication using async/await and Promises
	•	Integrated frontend services with backend REST APIs using Axios / Fetch
	•	Handled secure JWT storage and transmission on the client side
	•	Ensured responsive UI behavior across devices


🧩 Design Patterns Used
	•	Singleton Pattern – Ensures a single instance of Spring-managed beans
	•	Factory Pattern – Dynamic handling of user-related actions
	•	Builder Pattern – Lombok-based object construction
	•	Adapter Pattern – Redis integration abstraction
	•	Controller Pattern (MVC) – Structured request handling
	•	Command Pattern – Encapsulated execution logic for actions like email notifications



🖥️ User Interface
	•	Login and registration pages
	•	User dashboard for journals and checklists
	•	Admin dashboard for user management
	•	Fully responsive design



📦 Installation & Setup

Prerequisites
	•	Java 17+
	•	Node.js 18+
	•	npm
	•	MongoDB
	•	Redis

Backend Setup

git clone <repository-url>
cd backend
mvn clean install
mvn spring-boot:run

Frontend Setup

cd frontend
npm install
npm start



📌 Future Enhancements
	•	Advanced analytics dashboard
	•	Notifications and reminders
	•	AI-powered sentiment analysis
	•	Docker containerization
	•	CI/CD pipeline integration



📊 Results & Outcomes
	•	Successfully built and deployed a full-stack journaling and productivity platform with secure authentication and role-based access control
	•	Achieved end-to-end CRUD functionality for journals and checklists with reliable data persistence in MongoDB
	•	Improved API response efficiency through Redis-based caching and optimized service-layer logic
	•	Implemented JWT-secured REST APIs, ensuring stateless authentication and secure client–server communication
	•	Demonstrated effective use of Node.js and JavaScript tooling for frontend builds, dependency management, and environment configuration
	•	Applied multiple software design patterns to improve code maintainability, scalability, and separation of concerns
	•	Delivered responsive user and admin dashboards with seamless real-time updates
	•	Validated system stability through consistent frontend–backend integration and role-based authorization flows
