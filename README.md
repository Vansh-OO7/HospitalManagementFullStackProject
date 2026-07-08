#  MedManagePro – Hospital Management System

A modern Full Stack Hospital Management System built using **React** and **Spring Boot** that streamlines hospital operations such as patient management, doctor management, ward allocation, billing, and authentication.

---

##  Live Demo

 Frontend: **https://hospital-management-full-stack-project-5oqg57nvq.vercel.app/**

 Backend API: **https://hospitalmanagementfullstackproject.onrender.com/patients**

---

## 📸 Screenshots

<img width="1000" height="800" alt="image" src="https://github.com/user-attachments/assets/1c257a61-e9aa-4f58-a4eb-50a70c49dff6" />


#  Features

###  Doctor Management
- Add Doctor
- Update Doctor
- Delete Doctor
- View All Doctors

###  Patient Management
- Register Patient
- Update Patient Details
- Delete Patient
- Search Patients
- View Patient Records

###  Ward Management
- Add Wards
- View Ward Availability
- Assign Patients to Wards
- Ward Capacity Management

###  Billing System
- Generate Bills
- Calculate Charges
- View Billing Records

###  Dashboard
- Total Patients
- Total Doctors
- Total Wards
- Billing Statistics
- Real-time Hospital Overview

---

#  Tech Stack

## Frontend

- React.js
- Vite
- Tailwind CSS
- Axios
- React Router

## Backend

- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven

## Database

- MySQL (Aiven Cloud)

## Deployment

- Frontend → Vercel
- Backend → Render

## Version Control

- Git
- GitHub

---

#  Project Architecture

```
React Frontend
        │
        │ REST APIs
        ▼
Spring Boot Backend
        │
Spring Data JPA
        │
Hibernate ORM
        │
MySQL Database
```

---

#  Project Structure

```
HospitalManagementFullStackProject
│
├── HMS_Backend
│   └── HospitalManagementFinal
│       ├── controller
│       ├── service
│       ├── repository
│       ├── model
│       ├── security
│       └── config
│
└── HMS_FrontendBig
    └── HMS_Frontend
        ├── src
        ├── components
        ├── pages
        ├── services
        └── assets
```

---

#  Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/Vansh-OO7/HospitalManagementFullStackProject.git
cd HospitalManagementFullStackProject
```

---

## 2. Backend Setup

Navigate to the backend directory:

```bash
cd HMS_Backend/HospitalManagementFinal
```

Configure your MySQL database connection using `application.properties` (for local development) or environment variables.

Start the Spring Boot application:

```bash
mvn spring-boot:run
```

The backend will start on:

```
http://localhost:8080
```

---

## 3. Frontend Setup

Open a new terminal and navigate to the frontend directory:

```bash
cd HMS_FrontendBig/HMS_Frontend
```

Install the required dependencies:

```bash
npm install
```

Start the React development server:

```bash
npm run dev
```

The frontend will be available at:

```
http://localhost:5173
```

---
#  Future Enhancements

- User Authentication & Authorization (Spring Security + JWT)
- Appointment Booking System
- Email Notifications
- Prescription Management
- Medical Reports Upload
- Admin Dashboard
- Dark Mode
- Analytics Dashboard
- Export Reports as PDF

#  What I Learned

Through this project I gained practical experience in:

- Building scalable REST APIs
- React and Spring Boot integration
- Building RESTful APIs using Spring Boot
- Database design using MySQL
- ORM with Hibernate
- Cloud deployment on Render & Vercel
- Version control using Git and GitHub
- Debugging production deployments
- Full Stack application architecture

#  Author

**Vansh Butolia**

GitHub: https://github.com/Vansh-OO7
