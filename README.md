🧑‍💼 Employee Management System
<p align="center"> <img src="C:\6th sem\Full Stack\PROJECT\Employee Management\screenshots" alt="Employee Management System Banner" width="800"/> </p>

A production-ready Employee Management System built with
Spring Boot (Backend) and React + Tailwind CSS (Frontend).

Designed to demonstrate real-world full-stack development practices, clean architecture, and a modern UI.

✨ Features

✅ Employee Management

Add new employees

Update employee details

Delete employees

View all employees in a clean table

🔍 Powerful Search

Real-time search by name, email, or department

🛡️ Validation

Client-side form validation (React)

Server-side validation (Spring Boot)

🎨 Modern UI

Responsive dashboard

Clean layout using Tailwind CSS

Smooth UX for forms and tables

🛠️ Tech Stack
Backend
<p align="left"> <img src="https://img.shields.io/badge/Java-21-orange?style=for-the-badge&logo=java" /> <img src="https://img.shields.io/badge/Spring%20Boot-3-brightgreen?style=for-the-badge&logo=springboot" /> <img src="https://img.shields.io/badge/JPA-Hibernate-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/MySQL-8.0-blue?style=for-the-badge&logo=mysql" /> </p>
Frontend
<p align="left"> <img src="https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react" /> <img src="https://img.shields.io/badge/Vite-fast-yellow?style=for-the-badge&logo=vite" /> <img src="https://img.shields.io/badge/Tailwind%20CSS-4-38bdf8?style=for-the-badge&logo=tailwindcss" /> <img src="https://img.shields.io/badge/Axios-HTTP-blueviolet?style=for-the-badge" /> </p>
📋 Prerequisites

Make sure you have the following installed:

Java 17+

Node.js 18+

MySQL 8.0+

Maven

🚀 Setup Instructions
🗄️ 1. Database Setup

Open MySQL Workbench or MySQL CLI

Create the database:

CREATE DATABASE employee_management_system;


Configure database credentials in:

backend/src/main/resources/application.properties


(Default assumed: root/root)

⚙️ 2. Backend Setup (Spring Boot)

Navigate to the backend directory:

cd backend


Run the application:

mvn spring-boot:run


Backend will start at:

http://localhost:8080

🎨 3. Frontend Setup (React + Tailwind)

Navigate to the frontend directory:

cd frontend


Install dependencies:

npm install


Start the development server:

npm run dev


Frontend will run at:

http://localhost:5173

🔗 API Endpoints
Method	Endpoint	Description
GET	/api/employees	List all employees
POST	/api/employees	Add a new employee
GET	/api/employees/{id}	Get employee by ID
PUT	/api/employees/{id}	Update employee
DELETE	/api/employees/{id}	Delete employee
GET	/api/employees/search?query={query}	Search employees
🧪 Troubleshooting
❌ "mvn" is not recognized

This means Maven is not installed or not added to PATH.

✅ Option 1: Install via Winget (Recommended)
winget install Maven.Maven


➡ Restart VS Code / IntelliJ / Terminal after installation.

✅ Option 2: Refresh PATH (PowerShell)
$env:Path = [System.Environment]::GetEnvironmentVariable("Path","Machine") + ";" + [System.Environment]::GetEnvironmentVariable("Path","User")

✅ Option 3: Manual Installation

Download Maven from
👉 https://maven.apache.org/download.cgi

Extract it

Add the bin folder to System PATH

⚠️ Frontend Build Errors

Ensure you ran:

npm install


Tailwind CSS v4 requires:

@tailwindcss/postcss


📌 Project Highlights

Clean layered architecture

RESTful API design

Real-world validation & error handling

Modern frontend tooling

Resume-ready full-stack project

🙌 Author

Employee Management System


