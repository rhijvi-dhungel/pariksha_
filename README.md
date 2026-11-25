# 🎓 Pariksha – Examination Management System

**Pariksha** is a full-stack web-based Examination Management System developed to simplify examination administration and automate student seat allocation. It provides a centralized platform for organizing examination-related activities, managing student information, and generating structured seating arrangements.

## 📌 About the Project

Managing university examinations involves coordinating students, examination schedules, classrooms, and seating arrangements. Performing these tasks manually can be time-consuming and prone to organizational errors.

Pariksha aims to simplify this process through a centralized digital platform with an integrated Smart Seat Allocation system. It helps organize students into examination rooms based on examination requirements, batches, and available classroom capacities.

The project was developed as an academic group project by Computer Engineering students at Kathmandu University.

## ✨ Key Features

- **Examination Management:** Organize and manage examination-related information and schedules.
- **Student Management:** Maintain and organize student records and academic batches.
- **Smart Seat Allocation:** Automate student seating arrangements according to examination requirements.
- **Classroom Management:** Manage examination rooms and their seating capacities.
- **Batch Management:** Organize students according to their respective academic batches.
- **Examination Scheduling:** Manage examination routines and sessions.
- **Centralized Management:** Keep examination-related information organized within one platform.

## 🧠 Smart Seat Allocation

The Smart Seat Allocation feature is one of the central components of Pariksha.

It is designed to reduce the manual effort involved in preparing examination seating arrangements by organizing students according to:

- Examination sessions.
- Student batches.
- Subject requirements.
- Available examination rooms.
- Classroom seating capacities.

The system aims to make seating arrangements more systematic and efficient while simplifying examination administration.

## 🛠️ Technology Stack

### Frontend
- Next.js
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- Python
- FastAPI
- RESTful APIs

### Database
- PostgreSQL

### Development Tools
- Visual Studio Code
- Git
- GitHub
- Vercel
- Render

## 🏗️ System Architecture

Pariksha follows a three-layer full-stack architecture.

```text
          USER
            |
            v
    FRONTEND LAYER
       Next.js
        React
            |
            | HTTP Requests
            v
     BACKEND LAYER
        FastAPI
        Python
            |
            | SQL Queries
            v
     DATABASE LAYER
       PostgreSQL
```

**Frontend:** Handles the user interface and interactions using Next.js and React.

**Backend:** Processes requests, manages application logic, and provides REST APIs using FastAPI.

**Database:** PostgreSQL manages and stores application data.

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have installed:

- Node.js and npm
- Python 3
- PostgreSQL
- Git

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd pariksha
```

### 2. Frontend Setup

Navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Frontend will run at:

```text
http://localhost:3000
```

### 3. Backend Setup

Open another terminal and navigate to the backend directory:

```bash
cd backend
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

**Windows:**

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure the PostgreSQL database connection using the project's environment configuration.

Start the FastAPI server:

```bash
python -m uvicorn app:app --reload
```

*Note: Update directory names, application entry points, and configuration according to the actual repository structure.*

## 🌐 Deployment

The application is deployed using:

| Component | Platform |
|---|---|
| Frontend | Vercel |
| Backend | Render |
| Database | PostgreSQL |

**Live Application:** https://pariksha-vjxk.vercel.app/

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Full-stack web application development.
- Frontend development using Next.js and React.
- Backend development using Python and FastAPI.
- REST API development and integration.
- Relational database management using PostgreSQL.
- Designing automated seat allocation functionality.
- Frontend-backend communication.
- Collaborative software development using Git and GitHub.
- Application deployment.

## 🚀 Future Enhancements

- Advanced seat allocation optimization.
- Enhanced examination analytics and reporting.
- Improved attendance managements (digital) .
- Additional examination scheduling capabilities.
- More comprehensive administrative features.

---

**Pariksha – Simplifying Examination Management Through Technology.**
