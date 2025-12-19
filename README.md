
📔 **LifeLog**

**Secure Journaling & Checklist Web Application**

LifeLog is a full stack web application that allows users to maintain personal journal entries and daily checklists in a secure environment. The system includes authentication, role-based access control, and separate dashboards for users and administrators.



🧭 **Overview**

This project is designed to demonstrate full stack web development using a client–server architecture. The frontend communicates with the backend through RESTful APIs. Key goals of the project include security, scalability, and clean code structure.



✨ **Features**

	•	👤 User registration and login
	
	•	🔐 JWT-based authentication
	
	•	🛡️ Role-based access control for users and administrators
	
	•	📝 Create, view, update, and delete journal entries
	
	•	✅ Checklist creation and management
	
	•	👨‍💼 Admin functionality to manage user roles
	
	•	⚡ Redis caching to improve application performance



🛠️ **Technology Stack**

🎨 **Frontend**

	•	React
	
	•	Node.js
	
	•	npm

⚙️ **Backend**

	•	Java
	
	•	Spring Boot
	
	•	Spring Security
	
	•	Weather API

🗄️ Database & Caching

	•	MongoDB
	
	•	Redis



🏗️ **Architecture**


The frontend is developed using React and uses Node.js for dependency management and build processes. It interacts with the backend through secure REST APIs. The backend, built with Spring Boot, handles authentication, business logic, and data persistence. MongoDB is used for storing application data, and Redis is used to cache frequently accessed data to improve performance.



🔄 **Application Flow**


Users authenticate using a JWT-based login system. After logging in, users can access their dashboard to manage journal entries and checklists. Administrator users have additional permissions to manage user roles. All requests to protected endpoints are validated using JWT tokens to ensure security.



🧩 **Design Patterns Used**

	•	🔁 Singleton pattern for Spring-managed service classes
	
	•	🏭 Factory pattern for handling various user actions
	
	•	🧱 Builder pattern for creating entity objects
	
	•	🔌 Adapter pattern for Redis integration
	
	•	🎮 Controller pattern following the MVC architecture
	
	•	📦 Command pattern for executing specific operations



🚀 **Setup Instructions**

✅ **Prerequisites**

	•	Java 17 or higher
	
	•	Node.js
	
	•	npm
	
	•	MongoDB
	
	•	Redis

⚙️ **Backend Setup**

    •  mvn clean install
	
    •  mvn spring-boot:run

🎨 **Frontend Setup**

    •  npm install
	
    •  npm start
 


📊 **Results**

The application works reliably with secure authentication, stable frontend and backend communication, and proper data storage. The project demonstrates practical full stack development skills, effective use of REST APIs, and clean architectural design.

