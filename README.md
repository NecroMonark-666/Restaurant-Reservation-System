# Restaurant Reservation System

A full-stack Restaurant Reservation System built using React, Node.js, Express, MongoDB, and JWT Authentication.

## Features

### Customer
- User Registration & Login
- Book a Table
- View Reservations
- Cancel Reservations

### Admin
- Admin Login
- View All Reservations
- Manage Restaurant Tables
- Dashboard Statistics

## Tech Stack

### Frontend
- React
- TypeScript
- Vite
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs

## Project Structure

```
Restaurant-Reservation-System/
├── frontend/
│   ├── src/
│   ├── package.json
│   └── vite.config.ts
├── backend/
│   ├── src/
│   ├── package.json
│   └── .env.example
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/NecroMonark-666/Restaurant-Reservation-System.git
cd Restaurant-Reservation-System
```

### Backend

```bash
cd backend
npm install
```

Create `.env`

```env
PORT=5000
MONGO_URI=mongodb+srv://admin:Admin_66060@cluster0.mplckgq.mongodb.net/?appName=Cluster0
```

Run Backend

```bash
npm start
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

## API Endpoints

### Authentication

```
POST /api/auth/register
POST /api/auth/login
GET  /api/auth/me
```

### Reservations

```
GET    /api/reservations
POST   /api/reservations
PATCH  /api/reservations/:id/cancel
```

### Tables

```
GET    /api/tables
POST   /api/tables
PATCH  /api/tables/:id
```

## Author

**Samarth Pawar**

GitHub: https://github.com/NecroMonark-666
