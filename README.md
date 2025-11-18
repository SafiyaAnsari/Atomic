# Healthcare Wellness & Preventive Care Portal (MERN Stack)

This project is a simple MERN-based web application that focuses on preventive healthcare and basic wellness tracking. It includes two types of users: **Patients** and **Healthcare Providers**. Patients can log in to view their wellness stats and reminders, while providers can see an overview of patient progress.

---

##  Features

### Authentication
- Login and Registration for Patients and Providers
- Secure password hashing using **bcrypt**
- JWT-based authentication for protected routes

###  Patient Dashboard
- Displays daily wellness information:
  - Steps
  - Sleep hours
  - Active minutes
- Preventive care reminders (e.g., upcoming tests)
- “Health Tip of the Day” section
- Dashboard layout inspired by the provided mockups

###  Profile Section
- Update basic health information
- Fields include: age, gender, allergies, medications, etc.

###  Provider Dashboard
- Providers can view a list of registered patients
- Shows a simple compliance indicator based on goals/checkups



## Tech Stack

### Frontend
- **React (Vite)**
- Axios for API communication
- Context API for authentication handling
- Plain CSS (kept minimal and readable)

### Backend
- **Node.js + Express**
- MongoDB with Mongoose
- JWT for authentication
- Bcrypt for password hashing



---


---

##  API Endpoints 

### Auth
- `POST /api/auth/register`
- `POST /api/auth/login`
- `GET /api/auth/me`

### Wellness Data
- `GET /api/wellness`
- `POST /api/wellness`
- `PUT /api/wellness/:id`

### Reminders
- `GET /api/reminders`
- `POST /api/reminders`

### Provider
- `GET /api/provider/patients`

---







