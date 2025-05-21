# 🏥 Hospital Management System – MERN Stack Web Application

A complete full-stack hospital management system built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js) that allows seamless management of hospital operations such as patient records, appointments, doctor management, and administration dashboards.

---

## 📁 Project Structure

├── backend # Node.js + Express REST API

├── frontend # React frontend for hospital interface (patients/doctors)

├── dashboard # React dashboard interface (admin)



---

## 🚀 Features

### 👨‍⚕️ Frontend (Patient/Doctor Portal)
- Patient registration & login
- Book and view appointments
- Doctor login and schedule management
- Profile management

### 🛠 Dashboard (Admin Panel)
- Admin authentication
- Manage doctors, patients, appointments
- View real-time analytics and reports

### 🔧 Backend (API Server)
- RESTful APIs using Express
- JWT-based authentication
- MongoDB database connection and models
- Error handling and role-based access

---

## 💻 Tech Stack

- **Frontend:** React.js, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT
- **Dev Tools:** ESLint, Nodemon, Postman

---

## 🛠️ How to Run

### 📦 Install Dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install

# Dashboard
cd ../dashboard
npm install


▶️ Start Development Servers
# Start backend server
cd backend
npm run dev

# Start frontend client
cd ../frontend
npm run dev

# Start admin dashboard
cd ../dashboard
npm run dev

🔐 Environment Variables
Create a .env file inside /backend and configure:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000





