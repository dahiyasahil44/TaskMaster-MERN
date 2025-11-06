# ✅ TaskMaster Project

**TaskMaster** is an intuitive and collaborative task management platform designed to help users efficiently organize, track, and complete their tasks. It offers smart features like Kanban-style boards, deadline reminders, team collaboration, and AI-powered task completion predictions — all in one seamless experience.

**Project Type:** Full-Stack (MERN)

- 🌍 [**Live**](https://task-master-front-two.vercel.app/)

---

## 🧰 Tech Stack

- **Frontend:** React (Vite), Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT-based Authentication  
- **Deployment:** Vercel  

---

## ✨ Features

- 📝 **Task CRUD Operations:** Create, Read, Update, and Delete tasks with ease.  
- 📋 **Kanban Task Board:** Drag and drop tasks between columns — To-Do, In Progress, Completed.  
- ⏰ **Deadline Management:** Set task due dates and get reminder notifications.  
- 👥 **User Authentication:** Secure login/signup with role-based access (Admin & User).  
- 🤝 **Task Collaboration:** Assign tasks to multiple users and collaborate in real-time.  
- 💬 **Comments & Mentions:** Leave comments and tag other users for updates.  
- 🔗 **Secured Sharable Links:** Invite collaborators using time-bound secure links.  
- 🔁 **Recurring Tasks:** Create recurring tasks (daily, weekly, monthly) with automated reminders.  
- 🧩 **Custom Board Layouts:** Customize your task columns and save preferred layouts.  
- 🤖 **AI-Powered Insights:** Predict task completion timelines using AI.  
- 📱 **Responsive Design:** Works seamlessly on mobile, tablet, and desktop devices.  

---

## 📂 Project Structure

```bash
├── client/                      # Frontend (React + Vite)
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── utils/
│   │   └── App.jsx
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
│
├── server/                      # Backend (Node + Express)
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json
