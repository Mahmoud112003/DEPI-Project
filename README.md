# Medilo - Medical Platform

A full-stack medical platform that streamlines access to healthcare services, built as the graduation project for the Digital Egypt Pioneers Initiative (DEPI) - React Front-end Web Development track.

## Overview

Medilo connects patients with healthcare services through a modern, responsive web interface. The frontend is a React + TypeScript single-page application with centralized state management, and the backend is an Express + MongoDB REST API with JWT-based authentication and file upload support.

## Features

- User authentication and authorization (JWT)
- Responsive UI built for desktop and mobile
- Centralized state management with Redux Toolkit
- REST API with Express and MongoDB (Mongoose)
- Image/file uploads (Multer)
- Route-based navigation with React Router
- Toast notifications and carousel UI components

## Tech Stack

**Frontend:** React 19, TypeScript, Redux Toolkit, React Router, Axios, Bootstrap / React-Bootstrap, Vite

**Backend:** Node.js, Express 5, MongoDB (Mongoose), JWT, bcryptjs, Multer

## Project Structure

```text
DEPI-Project/
├── frontend/          # React + TypeScript SPA (Vite)
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       └── utils/
└── backend/           # Express + MongoDB API
    ├── config/
    ├── controllers/
    ├── middleware/
    ├── models/
    ├── routes/
    └── uploads/
```

## Getting Started

### Prerequisites
- Node.js 18+
- MongoDB (local or Atlas)

### Backend

```bash
cd backend
npm install
```

Create a `.env` file in `backend/`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Then start the server:

```bash
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

The app runs on the Vite dev server (default http://localhost:5173).

## Author

**Mahmoud Ayman** - [GitHub](https://github.com/Mahmoud112003) - [LinkedIn](https://www.linkedin.com/in/mahmoud-ayman55) - [Portfolio](https://mahmoud112003.github.io/Portfolio/)

Built as part of the DEPI Professional Certificate in React Front-end Web Development (MCIT).
