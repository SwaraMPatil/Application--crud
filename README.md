# 📝 MERN Stack Blog Website

A full-stack blog application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. This platform allows users to register, log in, and manage blog posts with Create, Read, Update, and Delete (CRUD) functionalities.

---

## 🚀 Live Demo

> 🔗 [Link to Live Project](#) *(Add your deployed site link here)*

---

## 🛠️ Tech Stack

- **MongoDB** – NoSQL database to store user and blog data.
- **Express.js** – Backend framework to handle API requests.
- **React.js** – Frontend library for building the UI.
- **Node.js** – Backend runtime for executing server-side code.
- **Axios** – For making HTTP requests.
- **React Router DOM** – Navigation and routing.
- **JWT (if used)** – For secure authentication.

---

## 📁 Project Structure

```bash
Blog-Website/
│
├── client/                 # Frontend (React)
│   ├── public/             # Static files
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Route-based pages (Home, Login, Register, etc.)
│   │   ├── App.js          # Main App with routes
│   │   └── index.js        # React DOM rendering
│
├── server/                 # Backend (Node + Express)
│   ├── controllers/        # Route logic
│   ├── models/             # MongoDB schemas
│   ├── routes/             # API routes
│   ├── .env                # Environment variables
│   └── index.js            # Server entry point

git clone https://github.com/kunaltyagi9/MERN-Stack-Projects.git
cd MERN-Stack-Projects/Blog-Website
