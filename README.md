# Task Manager (MERN Stack)

This is a simple Task Manager web application built using the MERN stack.  
The purpose of this project is to perform basic CRUD operations where a user can add tasks, view all tasks, and delete tasks.

This project was created as part of a technical task.

---

##Live Project Links
- Backend API URL: https://task-manager-backend-g21z.onrender.com

---

##Technologies Used

**Frontend**
- React
- Tailwind CSS
- JavaScript

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Deployment**
- Frontend deployed on Vercel / Netlify  
- Backend deployed on Render / Railway  
- Database hosted on MongoDB Atlas  

---

##Features

- Add a new task
- Display all tasks
- Delete a task
- Input validation for empty tasks
- Loading state while fetching data
- Simple and clean UI

---

##API Endpoints

- **POST /tasks** → Add a new task  
- **GET /tasks** → Fetch all tasks  
- **DELETE /tasks/:id** → Delete a task  

---

##How to Run the Project Locally

### Backend Setup

1. Clone the repository
```bash
git clone https://github.com/solankitushar123/Task-Manager-backend.git  

----

2.  Go to backend folder and install dependencies


cd backend
npm install
---

3. Create a .env file and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string


4 Start the backend server

node server.js

npm run dev




