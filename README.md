# MERN To-Do List Application

This is a full-stack MERN (MongoDB, Express, React, Node.js) application for managing a to-do list. Users can create, read, update, and delete tasks. Each task includes a title, description, status, and due date.

## Features

- **Create**: Add new tasks with a title, description, status, and due date.
- **Read**: View a list of all tasks with their details.
- **Update**: Edit the details of an existing task.
- **Delete**: Remove a task from the list.

## Live Demo

Check out the live demo of the application: https://to-do-mern-task-nine.vercel.app/.

## Technologies Used

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Deployment**: Vercel (Frontend), Render (Backend)

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. **Clone the repository**

```sh
git clone https://github.com/MOHDSAMIULLAH/to-do-MERN-Task.git
cd mern-to-do-list
```

2. **Setup Backend**

```sh
cd backend
npm install
```

Create a .env file in the server directory and add your MongoDB connection string:

```sh
# backend/.env
MONGO_URI=mongodb+srv://samiullah0813:samiullah0813@todomern.higmhwe.mongodb.net/?retryWrites=true&w=majority&appName=ToDoMERN
PORT=5000
```
Start the backend server:
```sh
  npm run dev
```

2. **Setup Frontend**
```sh
cd frontend
npm install
```
Create a .env file in the client directory:

```sh
# frontend/.env
REACT_APP_BASE_URL=http://localhost:5000/api

```
Start the frontend:
```sh
  npm start
```




