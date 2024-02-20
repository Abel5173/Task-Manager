# MERN Task Manager

A MERN application designed for streamlined task management. Perfect for keeping track of your to-dos with style and efficiency.

![Task Manager](image-link-here) <!-- Replace `image-link-here` with the actual link to your image -->

## Table of Contents

- [Features](#features)
  - [User-side Features](#user-side-features)
  - [Developer-side Features](#developer-side-features)
- [Tools and Technologies](#tools-and-technologies)
- [Dependencies](#dependencies)
- [Dev-dependencies](#dev-dependencies)
- [Prerequisites](#prerequisites)
- [Installation and Setup](#installation-and-setup)
- [Backend API](#backend-api)
- [Frontend Pages](#frontend-pages)
- [npm Scripts](#npm-scripts)
- [Useful Links](#useful-links)

## Features

### User-side Features

- Signup, Login, Logout
- Add, View, Update, Delete tasks

### Developer-side Features

- Toasts for success and error messages
- Form validations in frontend and backend
- Fully Responsive Navbar
- Token based Authentication
- Use of 404 page for wrong URLs
- Relevant redirects
- Global user state using Redux
- Custom Loaders
- Use of layout component for pages
- Use of theme colors
- No external CSS files needed (Tailwind CSS)
- Usage of Tooltips
- Dynamic document titles
- Redirect to previous page after login
- Use of various React hooks
- Custom hook (useFetch)
- Routes protection
- Middleware for verifying the user in backend
- Use of different HTTP status codes for sending responses
- Standard practices followed

## Tools and Technologies

- HTML, CSS, JavaScript
- Tailwind CSS
- Node.js, Express.js
- React, Redux
- MongoDB

## Dependencies

- `axios`
- `react`
- `react-dom`
- `react-redux`
- `react-router-dom`
- `react-toastify`
- `redux`
- `redux-thunk`
- `bcrypt`
- `cors`
- `dotenv`
- `express`
- `jsonwebtoken`
- `mongoose`

## Dev-dependencies

- `nodemon`
- `concurrently`

## Prerequisites

- Node.js must be installed on the system.
- A MongoDB database.
- A code editor (VS Code recommended).

## Installation and Setup

1. **Install all dependencies**

   ```bash
   npm run install-all
   ```

2. **Setup Environment**

   Create a file named `.env` inside the backend folder. Use the `.env.example` as a reference and add your credentials.

3. **Start the Application**

   ```bash
   npm run dev
   ```

   Visit [http://localhost:3000](http://localhost:3000)

## Backend API

- `POST /api/auth/signup`
- `POST /api/auth/login`
- `GET /api/tasks`
- `GET /api/tasks/:taskId`
- `POST /api/tasks`
- `PUT /api/tasks/:taskId`
- `DELETE /api/tasks/:taskId`
- `GET /api/profile`

## Frontend Pages

- `/` Home Screen (Public home page for guests and private dashboard for logged-in users)
- `/signup` Signup page
- `/login` Login page
- `/tasks/add` Add new task
- `/tasks/:taskId` Edit a task

## npm Scripts

**At root:**

- `npm run dev`: Starts both backend and frontend
- `npm run dev-server`: Starts only backend
- `npm run dev-client`: Starts only frontend
- `npm run install-all`: Installs all dependencies.

**Inside frontend folder:**

- `npm start`: Starts frontend in development mode.
- `npm run build`: Builds the frontend for production.
- `npm test`: Launches the test runner.
- `npm run eject`: Removes the single build dependency.

**Inside backend folder:**

- `npm run dev`: Starts backend using nodemon.
- `npm start`: Starts backend without nodemon.

## Useful Links

**This project**

- [Github Repo](https://github.com/aayush301/MERN-task-manager)

**Official Docs**

- [Reactjs docs](https://reactjs.org/docs/getting-started.html)
- [npmjs docs](https://docs.npmjs.com/)
- [Mongodb docs](https://docs.mongodb.com/manual/introduction/)
- [Github docs](https://docs.github.com/en
