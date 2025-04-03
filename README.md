# Doctor Appointment System

## 📌 Description

The **Doctor Appointment System** is a modern, web-based application designed to streamline the process of booking and managing medical appointments between doctors and patients. The system offers a user-friendly interface for patients and doctors, along with a robust admin panel for overseeing the entire system.

## 🌟 Features

- 🔒 **User Authentication**: Secure login and registration for both doctors and patients.
- 📝 **Profile Management**: View, update, and manage user profiles.
- 📅 **Appointment Management**: Book, view, update, and cancel appointments with ease.
- 🛡️ **Admin Panel**: Admin functionalities to manage doctors and patients effectively.
- 📱 **Responsive UI**: Enhanced user experience across various devices.

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

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by **Chirukuri Manohar**

