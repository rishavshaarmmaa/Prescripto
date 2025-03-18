# Prescripto - Full Stack Doctor Appointment Booking System

## Project Overview
Prescripto is a **Full Stack Doctor Appointment Booking System** built using the **MERN Stack (MongoDB, Express.js, React.js, and Node.js)**. This project provides a seamless platform for **patients, doctors, and admins** to manage appointments efficiently. It supports online payments, user authentication, and role-based dashboards for better healthcare management.

### **Live Demo**
- **Website (Patient Portal):** [Prescripto Frontend](https://prescripto-frontend-d8l9.onrender.com)
- **Admin Dashboard:** [Prescripto Admin](https://prescripto-admin-wmow.onrender.com)

## Features
### **1. Patient Features**
- Register/Login using secure authentication
- Book appointments with available doctors
- Manage booked appointments
- Make online payments for consultations

### **2. Doctor Features**
- Secure login for doctors
- View and manage appointments
- Track earnings from consultations
- Update doctor profile

### **3. Admin Features**
- Manage doctor profiles
- Monitor and manage all appointments
- Oversee platform analytics and earnings

## Technologies Used
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ORM)
- **Authentication:** JSON Web Token (JWT)
- **Payments:** Integrated online payment gateway
- **Hosting:** Render (Frontend & Backend)

## Installation Guide
Follow these steps to set up the project on your local machine:

### **1. Clone the Repository**
```sh
git clone https://github.com/your-username/prescripto.git
cd prescripto
```

### **2. Backend Setup**
```sh
cd backend
npm install
```

Create a **.env** file inside the backend directory and add the following:
```env
MONGODB_URI="your_mongodb_connection_string"
JWT_SECRET="your_jwt_secret"
ADMIN_EMAIL="admin@example.com"
ADMIN_PASSWORD="your_admin_password"
CURRENCY="INR"
```

Start the backend server:
```sh
npm start
```

### **3. Frontend Setup**
```sh
cd ../frontend
npm install
npm start
```

### **4. Admin Panel Setup**
```sh
cd ../admin
npm install
npm start
```

## Usage
- Visit the **patient portal** to book appointments.
- Doctors can log in to manage their schedules.
- Admins have access to manage users and doctors.

## Contributing
Feel free to fork the repository and submit pull requests to enhance the project.

## License
This project is **MIT Licensed**. You can use and modify it freely for your personal or academic projects.

---
Developed with ❤️ by **Rishav Raj**
