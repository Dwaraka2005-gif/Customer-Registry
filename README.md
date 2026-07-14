# MERN CRM - Customer Management System

## Overview

MERN CRM is a full-stack Customer Relationship Management (CRM) application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The system helps organizations efficiently manage customers, companies, contacts, deals, tasks, and user authentication through a modern web interface.

---

## Features

- User Authentication
- Dashboard with Analytics
- Customer Management
- Company Management
- Contact Management
- Deal Management
- Task Management
- REST API
- Secure JWT Authentication
- Responsive User Interface

---

## Technology Stack

### Frontend
- React.js
- Vite
- Redux Toolkit
- Tailwind CSS
- Chart.js

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

### Development Tools
- Git & GitHub
- VS Code
- Postman

---

## Project Structure

```
mern-crm-dev/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── src/
│   ├── openapi.yaml
│   ├── server.js
│   └── package.json
│
├── README.md
└── ROADMAP.md
```

---

## Installation

### Clone Repository

```bash
git clone <repository-url>
```

### Install Frontend

```bash
cd client
npm install
```

### Install Backend

```bash
cd ../server
npm install
```

---

## Environment Variables

Create a `.env` file inside the server folder and configure the required environment variables.

Example:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

## Run Project

Backend

```bash
npm run dev
```

Frontend

```bash
npm run dev
```

---

## Modules

- Authentication Module
- Dashboard Module
- Customer Module
- Company Module
- Contact Module
- Deal Module
- Task Module

---

## API Documentation

The API documentation is available in:

```
server/openapi.yaml
```

---

## Future Enhancements

- Email Notifications
- Role-Based Access Control
- Calendar Integration
- Advanced Reports
- Cloud Deployment

---

## Author
P.Dwaraka
