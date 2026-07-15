# 🎉 Events App

A full-stack event management application where users can create accounts, authenticate securely, and manage events.

The project is built using **React** for the frontend and **Node.js + Express** for the backend. It demonstrates authentication, protected routes, REST API development, and modern React Router features.

---

## 📌 Project Overview

This application allows users to:

- Create a new account
- Login securely
- View available events
- View event details
- Create new events
- Edit existing events
- Delete events
- Access protected pages only after authentication

Authentication is handled using **JWT (JSON Web Token)**, with protected backend routes and frontend route protection.

---

# ✨ Features

## 🔐 Authentication

- User registration
- User login
- Password encryption using bcrypt
- JWT token authentication
- Protected routes
- Automatic logout after token expiration
- Authentication middleware on the backend

---

## 📅 Events Management

- Display all events
- Display single event details
- Create new events
- Update existing events
- Delete events
- Event validation
- Error handling

---

## ⚛️ Frontend Features

- React 18
- React Router DOM v6
- Data Router (Loaders & Actions)
- Protected routes
- Form handling
- Reusable components
- CSS Modules styling

---

## 🚀 Backend Features

- REST API with Express.js
- Authentication middleware
- JWT verification
- Password hashing
- Request validation
- Error handling
- Modular project structure

---

# 🛠️ Technologies

## Frontend

| Technology | Purpose |
|---|---|
| React.js | User interface |
| React Router DOM | Routing and navigation |
| JavaScript ES6+ | Programming language |
| CSS Modules | Component styling |

---

## Backend

| Technology | Purpose |
|---|---|
| Node.js | Runtime environment |
| Express.js | Backend framework |
| JSON Web Token | Authentication |
| bcryptjs | Password hashing |

---

# 📂 Project Structure

```
events-app
│
├── backend
│   │
│   ├── app.js
│   ├── routes
│   │   ├── auth.js
│   │   └── events.js
│   │
│   ├── util
│   │   ├── auth.js
│   │   ├── errors.js
│   │   └── validation.js
│   │
│   ├── data
│   │   ├── event.js
│   │   └── users.js
│   │
│   └── package.json
│
│
└── frontend
    │
    ├── src
    │   │
    │   ├── components
    │   ├── pages
    │   ├── util
    │   ├── App.js
    │   └── index.js
    │
    └── package.json
```

---

# ⚙️ Installation

## Requirements

Make sure you have installed:

- Node.js
- npm

Check versions:

```bash
node -v
npm -v
```

---

# 🔧 Backend Setup

Navigate to backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Start backend server:

```bash
npm start
```

Backend will run on:

```
http://localhost:8080
```

---

# 🎨 Frontend Setup

Open another terminal:

Navigate to frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start React application:

```bash
npm start
```

Frontend will run on:

```
http://localhost:3000
```

---

# 🔒 Security

The application includes:

- Password hashing
- JWT authentication
- Protected API routes
- Token expiration handling
- Input validation

---


# 🚧 Future Improvements

Future features planned:

- [ ] Upload event images
- [ ] Store data using MongoDB
- [ ] User profile pages
- [ ] Search events
- [ ] Event categories
- [ ] Pagination
- [ ] Deploy application
- [ ] Add automated tests

---

# 👨‍💻 Author

## Ibrahim Yasser

Software Engineer

GitHub:

```
https://github.com/ibrahimyasser450
```

---
