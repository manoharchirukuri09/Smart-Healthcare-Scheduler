# Doctor Appointment System

## 📌 Description

The **Doctor Appointment System** is a comprehensive, web-based application designed to streamline the process of scheduling, managing, and monitoring medical appointments. It provides role-based access for **patients**, **doctors**, and **admin users**, ensuring a smooth workflow for all parties involved. The application is built with a robust backend using **Node.js and Express**, with data management handled by **MongoDB**. The frontend is developed with **React**, ensuring a dynamic and responsive user experience.

## 🌟 Features

### 🔒 User Authentication
- Secure login and registration for both doctors and patients.
- Password hashing using bcrypt for enhanced security.
- Role-based access control with JWT authentication to distinguish between patients, doctors, and admin users.
- Forgot password functionality for enhanced user convenience.

### 📝 Profile Management
- Patients and doctors can create, view, and update their profiles.
- Doctors can specify their specialization, availability, contact details, and consultation fees.
- Patients can maintain personal information, medical history, and past appointments.
- Profile pictures can be uploaded and updated for better identification.

### 📅 Appointment Management
- Easy appointment booking with available doctors based on specialization, date, and time.
- View, edit, or cancel appointments with instant updates.
- Appointment history tracking for both patients and doctors.
- Doctors can set their availability schedule to avoid conflicts.

### 🛡️ Admin Panel
- Comprehensive admin dashboard for monitoring the entire system.
- Ability to add, update, or remove doctor profiles.
- View and manage all registered users and their roles.
- Monitor all appointments in the system with real-time updates.
- Generate statistical reports and logs for system monitoring and decision-making.
- Enhanced security with role-based permission handling.

### 📱 Responsive UI
- Fully responsive design ensuring seamless usage on desktops, tablets, and mobile devices.
- Intuitive user interface with clean and modern styling.
- Dark mode support for better accessibility.



---

## 🚀 Installation

### Prerequisites

- Install [Node.js](https://nodejs.org/).
- Install [MongoDB](https://www.mongodb.com/).
- Install [Visual Studio Code](https://code.visualstudio.com/) or your preferred IDE.

### Clone the Repository

```bash
    git clone <repository-url>
    cd Doctor-Appointment-System
```

### Install Dependencies

```bash
    npm install
```

---

## 📖 Usage

### Running the Application

1. **Start the MongoDB Server:**

```bash
    mongod
```

2. **Run the Application:**

```bash
    npm start
```

3. **Open your browser and visit:**

```
    http://localhost:3000
```

---

## 📁 Project Structure

- **Backend:** Node.js, Express, MongoDB
- **Frontend:** HTML, CSS, JavaScript, React

---

## 🔗 API Endpoints

### Authentication
- `POST /api/register` - Register a new user.
- `POST /api/login` - Authenticate user.

### Doctors
- `GET /api/doctors` - Retrieve a list of doctors.
- `POST /api/doctors` - Add a new doctor (Admin only).

### Patients
- `GET /api/patients` - Retrieve a list of patients.
- `POST /api/patients` - Add a new patient (Admin only).

### Appointments
- `GET /api/appointments` - Retrieve all appointments.
- `POST /api/appointments` - Book a new appointment.
- `DELETE /api/appointments/:id` - Cancel an appointment.

---

## 💻 Technologies Used

- **Frontend:** HTML, CSS, JavaScript, React
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens), bcrypt
- **Styling:** Tailwind CSS
- **Charts & Graphs:** Recharts, Chart.js
- **Notifications:** NodeMailer, Twilio

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by **Chirukuri Manohar**

