# Task Management Application (MERN Stack)

## Overview
This project is a simple task management application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create, update, and delete tasks, organized by status. The application provides a user-friendly interface and responsive design for both desktop and mobile devices.

## Technologies Used
- **Frontend:** React.js, Angular, CSS/SASS, HTML
- **Backend:** Node.js, Express.js
- **Database:** MongoDB

## Setup Instructions
1. Clone the repository to your local machine: `git clone https://github.com/your-username/task-management-app.git`
2. Navigate to the project directory: `cd task-management-app`
3. Install dependencies for both frontend and backend:
   - Frontend: `cd frontend && npm install`
   - Backend: `cd backend && npm install`
4. Start the backend server: `cd backend && npm start`
5. Start the frontend development server: `cd frontend && npm start`
6. Open your browser and navigate to `http://localhost:3000` to view the application.

## Project Structure
task-management-app/

│

├── backend/

│ ├── controllers/

│ ├── models/

│ ├── routes/

│ └── app.js

│

└── frontend/

├── public/

├── src/

│ ├── components/

│ ├── pages/

│ ├── App.js

│ ├── index.js

│ └── ...

│

└── ...


## API Documentation
The backend provides the following API endpoints:

- `GET /api/tasks`: Retrieve all tasks
- `POST /api/tasks`: Create a new task
- `PUT /api/tasks/:taskId`: Update an existing task
- `DELETE /api/tasks/:taskId`: Delete a task

## Demo Video
Watch the demo video on [loom](https://www.loom.com/share/484462b802014b25b0f4d23abb7ae056?sid=fc7da129-0d92-49e4-9aae-2c9d0386e5e9)! 


> Don't forget to run `npm install` in both the **api** and **frontend** folders to install dependencies
