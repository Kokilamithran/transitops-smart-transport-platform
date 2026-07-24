# TransitOps - Smart Transport Operations Platform

TransitOps is an **end-to-end logistics and transport operations management system** built as a full-stack web application.

The project brings together a **Spring Boot REST API**, a modern **React frontend**, and database-backed transport operations into a single platform.

TransitOps was developed collaboratively as part of a **team hackathon project**. This repository showcases the project and the areas I contributed to during development.

---

## Tech Stack

### Backend

* Java
* Spring Boot
* Spring REST
* Spring Data JPA
* Spring Security
* Maven
* MySQL

### Frontend

* React 19
* Vite
* JavaScript
* Tailwind CSS v4
* Zustand
* GSAP

### Tools

* Git
* GitHub
* Maven
* npm

---

## Architecture

TransitOps follows a full-stack client-server architecture.

```text
┌───────────────────────────────────┐
│          React Frontend           │
│                                   │
│ React 19 • Vite • Tailwind CSS    │
│       Zustand • GSAP              │
└─────────────────┬─────────────────┘
                  │
                  │ REST API
                  ▼
┌───────────────────────────────────┐
│        Spring Boot Backend        │
│                                   │
│ Controllers → Services → Repos    │
│        Spring Security            │
└─────────────────┬─────────────────┘
                  │
                  │ JPA
                  ▼
┌───────────────────────────────────┐
│              MySQL                │
│                                   │
│        Application Data           │
└───────────────────────────────────┘
```

### Application Flow

```text
User
  ↓
React Frontend
  ↓
REST API
  ↓
Spring Boot Controller
  ↓
Service Layer
  ↓
Repository Layer
  ↓
MySQL Database
```

This separation keeps the user interface, business logic, security, and persistence layers independently maintainable.

---

## Key Features

* Full-stack logistics and transport operations management
* React-based user interface
* REST API communication between frontend and backend
* User registration and authentication
* Spring Security integration
* MySQL database persistence
* Centralized state management using Zustand
* Responsive interface using Tailwind CSS
* UI animations using GSAP
* Layered Spring Boot backend architecture

---

## My Contributions

My work on TransitOps covered multiple areas of the full-stack application:

* Spring Boot backend development
* React frontend development
* REST API development and integration
* MySQL database integration
* Authentication and security
* Spring Security configuration
* Frontend/backend integration
* Debugging and integration
* Git and GitHub collaboration

Working across the stack gave me practical experience connecting the frontend, backend, security, and database layers of a larger application.

---

## Running the Project

### Prerequisites

Make sure you have the following installed:

* Java
* Node.js
* npm
* MySQL
* Git

---

### Clone the Repository

```bash
git clone https://github.com/Kokilamithran/transitops-smart-transport-platform.git
cd transitops-smart-transport-platform
```

---

### Running the Frontend

Install the dependencies:

```bash
npm install
```

Start the Vite development server:

```bash
npm run dev
```

---

### Running the Backend

Build and run the Spring Boot application using the Maven wrapper:

```bash
./mvnw spring-boot:run
```

On Windows PowerShell, you can use:

```powershell
.\mvnw.cmd spring-boot:run
```

Make sure the required MySQL database configuration is set correctly before starting the backend.

---

## What I Learned

TransitOps gave me hands-on experience with:

* Building REST APIs with Spring Boot
* Developing interfaces using React
* Connecting React applications to Java backends
* Working with MySQL and JPA
* Implementing authentication and application security
* Managing frontend state using Zustand
* Working with a modern Vite-based frontend
* Debugging full-stack integration issues
* Using Git and GitHub in a collaborative project
* Integrating work developed by multiple team members

---

## Screenshots

Screenshots of the application will be added here.

Recommended screenshots:

* Login / Registration
* Dashboard
* Transport operations interface
* Major management features

---

## Future Improvements

* Deployment of the complete application
* Expanded role-based access control
* Improved dashboards and analytics
* Additional transport management features
* Automated testing
* Improved error handling and validation
* Real-time operational updates

---

## Project Context

TransitOps was developed collaboratively as part of a **team hackathon project**.

This repository is maintained as a personal showcase of the project and the development areas I contributed to.

---

## Author

**Kokilamithran S**

B.Tech Information Technology
Sri Krishna College of Technology
Expected Graduation: 2028

* GitHub: https://github.com/Kokilamithran
* LinkedIn: https://www.linkedin.com/in/kokilamithran-s-8a89ab325/
* LeetCode: https://leetcode.com/u/KokilamithranS/

---

**Built, debugged, integrated, and improved through hands-on full-stack development.**
