# User Management Web Application

This project is a full-stack web application for managing users. The frontend is developed using Angular, and the backend is developed using NestJS. The application allows users to create, view, edit, and delete user information and generate, download, and view PDF documents containing user data.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Features

- Create, view, edit, and delete user information.
- Display user information in a table.
- Generate PDF documents based on user data.
- Download and view generated PDF documents.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [Angular CLI](https://angular.io/cli) (version 12 or higher)
- [NestJS CLI](https://docs.nestjs.com/cli/overview) (version 7 or higher)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Pratham9798/user-management.git
   cd user-management
   Install dependencies for both the frontend and backend.
   
Frontend (Angular)

cd frontend
npm install
Backend (NestJS)

cd backend
npm install
Running the Application
Backend (NestJS)
Navigate to the backend directory:

cd backend
Start the NestJS server:

npm run start
The server will run on http://localhost:3000.

Frontend (Angular)
Navigate to the frontend directory:

cd frontend
Start the Angular development server:

ng serve
The Angular app will run on http://localhost:4200.

Usage
Open your browser and navigate to http://localhost:4200.
Use the form to add new users.
View the list of users in the table.
Edit or delete users using the corresponding buttons.
Generate a PDF of the user list by clicking the "Generate PDF" button.
Download the PDF by clicking the "Download PDF" button.
View the generated PDF within the application.
API Endpoints
User Management
GET /users: Retrieve all users.
POST /users: Add a new user.
PUT /users/
: Update a user by ID.
DELETE /users/
: Delete a user by ID.
PDF Generation
GET /pdf/generate: Generate a PDF document containing user data.
Project Structure
The project is divided into two main parts: frontend and backend.

Frontend (Angular)
src/app/form - Form component for adding users.
src/app/table - Table component for displaying users.
src/app/integration - Parent component integrating form and table.
src/app/pdf-viewer - Component for viewing PDFs.
src/app/services/user.service.ts - Service for interacting with user API.
src/app/services/pdf.service.ts - Service for PDF generation.
Backend (NestJS)
src/user - User module, controller, and service.
src/pdf - PDF module, controller, and service.

