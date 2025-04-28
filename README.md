# Hospital Management System

## Project Overview

The **Hospital Management System** is a web application built using the MERN stack (MongoDB, Express, React, Node.js) to manage various aspects of a hospital's operations, including appointments, user management, and doctor management. The application features both a user and admin mode, allowing users to book appointments and admins to manage doctors and approve/reject appointments.

## Features

- **Good Landing Page**: A clean and modern landing page to introduce the system and guide users to different sections.
- **Send Message**: Users can send messages, such as inquiries or requests, to the admin or support team.
- **Login & Signup**: Users can create accounts and log in securely to access their profiles and book appointments.
- **User(Patient) and Admin Mode**: 
  - **User(Patient)**: Can fill out an appointment form and request an appointment.
  - **Admin**: Can manage users, approve or reject appointment requests, and add doctors.
- **Appointment Booking**: Users can fill out a form to book an appointment with a doctor of their choice.
- **Token Verification**: JWT-based authentication to securely verify user actions and ensure safe access to user-specific data.
- **Good Dashboard UI**: A user-friendly and responsive dashboard with a modern UI for both users and admins.
- **Responsive Design**: The application is fully responsive, ensuring a seamless experience on both mobile and desktop devices.

## Tech Stack

- **Frontend**: 
  - React.js
  - Vite (Development server)
  - Tailwind CSS (For styling)
  - React Router (For navigation)
  - Axios (For API calls)
  - React Toastify (For notifications)
  
- **Backend**: 
  - Node.js with Express.js
  - MongoDB with Mongoose (For database)
  - JWT (For authentication)
  - Bcrypt (For hashing passwords)
  - Cloudinary (For image storage)


  - **Folder structure**: 
hospital-management-system/
│
├── backend/                # Backend server (Node.js/Express)
│   ├── controllers/        # Route handlers
│   ├── models/             # Mongoose models
│   ├── routes/             # API routes
│   ├── config/             # Configuration files (DB, Cloudinary)
│   └── server.js           # Main server file
│
├── frontend/               # Frontend (React)
│   ├── components/         # Reusable components
│   ├── pages/              # Pages for different routes
│   └── App.js              # Main entry point for React app
│
└── dashboard/              # Admin Dashboard (React)
    ├── components/         # Admin-specific components
    ├── pages/              # Admin pages (Appointments, Doctors, etc.)
    └── App.js              # Main entry point for the admin dashboard

