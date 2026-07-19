# 🏠 FixIt – Home Repair Manager

A **Full Stack Web Application** that helps users organize and manage household maintenance tasks efficiently. FixIt allows users to create, update, track, and manage home repair activities such as plumbing, electrical work, appliance servicing, and general maintenance, ensuring that important repairs are never missed.

---

## 📖 Project Overview

Managing home maintenance manually can lead to missed servicing schedules and costly repairs. **FixIt** provides a centralized platform where users can keep track of maintenance tasks, monitor due dates, and organize repair activities through an intuitive dashboard.

---

## ✨ Features

- 🔐 Secure User Authentication (Sign Up & Login)
- 📝 Create, Update, Delete, and View Maintenance Tasks
- 📅 Track Upcoming Maintenance Schedules
- 🔍 Search and Filter Tasks
- 📱 Responsive User Interface
- 🗂️ Personalized Dashboard for Each User
- 🔒 Password Encryption for Secure Authentication

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Tools & Technologies
- Git
- GitHub
- VS Code
- Postman

---

## 📂 Project Structure

```
FixIt-Home-Repair-Manager/
│
├── client/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── pages/
│   └── index.html
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
├── README.md
└── .gitignore
```

---

## 📸 Screenshots

### Login Page
![Login](screenshots/login.png)

### Sign Up Page
![Sign Up](screenshots/signup.png)

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Add Task
![Add Task](screenshots/add-task.png)

### Task List
![Task List](screenshots/task-list.png)

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/lochana-12/FixIt-Home-Repair-Manager.git
```

### Navigate to the project

```bash
cd FixIt-Home-Repair-Manager
```

### Install dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the server directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Start the server

```bash
npm start
```

or

```bash
npm run dev
```

---

## 💻 Usage

1. Register a new account.
2. Login using your credentials.
3. Add maintenance tasks.
4. Edit or delete existing tasks.
5. Track upcoming maintenance schedules from the dashboard.

---

## 📌 REST API Endpoints

### Authentication

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/register` | Register a new user |
| POST | `/login` | Login user |

### Tasks

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/tasks` | Get all tasks |
| POST | `/tasks` | Add a new task |
| PUT | `/tasks/:id` | Update a task |
| DELETE | `/tasks/:id` | Delete a task |

---

## 🗃️ Database Collections

### Users

- Name
- Email
- Password (Encrypted)

### Tasks

- Task Name
- Description
- Category
- Due Date
- Status
- Frequency
- User ID

---

## 🎯 Future Enhancements

- 📧 Email Notifications
- 📱 SMS Reminders
- 🔔 Push Notifications
- 📊 Maintenance Analytics
- 🖼️ Image Uploads
- 👨‍🔧 Service Provider Integration
- 🌐 Multi-language Support
- 📅 Calendar Integration

---

## 📸 Screenshots

Add screenshots of:

- Login Page
- Registration Page
- Dashboard
- Add Task Page
- Task List

---

## 🤝 Contributors

- **Lochana Vasamsetti** – User Authentication & Form Validation
- **Navya Lalitha Vardhanapu** – Frontend UI & Responsive Design
- **Lochana Yerra** – Task Management & Dashboard

---

## 🎓 Learning Outcomes

Through this project, we gained practical experience in:

- Full Stack Web Development
- REST API Development
- MongoDB Database Integration
- User Authentication
- CRUD Operations
- Responsive Web Design
- MVC Architecture
- Git & GitHub Version Control

---


---

⭐ If you found this project useful, don't forget to **Star** the repository!
