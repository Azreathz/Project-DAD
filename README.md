# Clinic Management System

A Java-based desktop application designed to manage clinic operations including patient appointments, profile management, and healthcare provider interactions.

## 🏥 Overview

This system enables patients to:

- Book appointments with available doctors
- Select appointment date and time
- Update their personal profiles
- View nearby pharmacies for convenience

Doctors can:

- View all upcoming and past appointments
- Update appointment statuses (e.g., completed, cancelled)
- Reschedule appointments when needed

All data is managed via a MySQL database backend, and the user interface is built using Java Swing.

---

## 🚀 Features

### 👤 Patient Module
- Register and log in
- View and update personal profile
- Book appointments
- Reschedule or cancel upcoming appointments
- View a list of nearby pharmacists

### 🩺 Doctor Module
- View all scheduled appointments
- Update appointment status
- Reschedule appointments

### 🛠 Admin/Shared Features (Optional)
- User management
- View logs or history

---

## 🧰 Technologies Used

- **Java (JDK 17+)**
- **Swing** for GUI
- **MySQL** for relational data storage
- **Java HttpServer** for internal API communication
- **JSON** for data transfer format
- **JDBC** for database connectivity

---

## 🖥 Installation & Running

1. Clone or download this repository.
2. Set up a MySQL database and import the provided schema (usually `clinicdb.sql`).
3. Edit the `DBConnection.java` file to match your local database credentials.
4. Open the project in an IDE like IntelliJ or Eclipse.
5. Run `Main.java` (or your main GUI launcher class).
6. Make sure your backend API server (HttpServer) is also running.

---

## 📸 Screenshots

*(Add screenshots here if available)*  
Example:
- Patient booking interface  
- Doctor dashboard  
- Profile update form

---

## 🔒 License

This project is open-source and licensed under the [MIT License](LICENSE).

---

## 🤝 Contributions

Contributions are welcome! Please fork this repo and create a pull request.

