<p align="center">
  <img src="https://img.icons8.com/color/480/rfid-signal.png" width="130"/>
</p>

<h1 align="center">📡 RFID Attendance System using ESP32</h1>

<p align="center">
  🚀 Smart | Contactless | IoT-Based Attendance Tracking System  
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-IoT-blue?style=for-the-badge&logo=espressif" />
  <img src="https://img.shields.io/badge/RFID-RC522-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Arduino-C%2FC++-orange?style=for-the-badge&logo=arduino" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

---

# 📡 RFID Attendance System using PHP & ESP32

🚀 A complete **RFID-based Attendance Management System** integrated with **ESP32, PHP, and MySQL** for real-time attendance tracking. This system automatically records attendance when an RFID card is scanned and displays it on a web dashboard.

---

## 📌 Description

This project is an IoT-based attendance system where RFID cards are used to mark attendance. The ESP32 reads the RFID UID and sends it to a PHP server. The backend stores the data in a MySQL database and displays it through a web interface. It eliminates manual attendance and ensures accuracy, speed, and security.

---

## ✨ Features

* 📡 RFID card scanning using ESP32
* ⚡ Real-time attendance update
* 🗓️ Date & time logging
* 👨‍💼 Admin login system
* 👥 User management (Add/Update users)
* 📊 Attendance logs display
* 📥 Export attendance to Excel
* 🌐 Web-based dashboard

---

## 🛠️ Tech Stack

* **Hardware:** ESP32, RFID Module (RC522)
* **Backend:** PHP
* **Database:** MySQL
* **Frontend:** HTML, CSS, JavaScript
* **Server:** XAMPP / WAMP

---

## 🧠 How It Works

1. RFID card is scanned
2. ESP32 reads UID
3. UID sent to PHP server via HTTP
4. PHP stores data in MySQL database
5. Attendance displayed on dashboard
6. Admin can manage users and export data

---

## 📂 Project Structure

```id="r3k8dp"
RFID-Attendance-System/
│── index.php
│── login.php
│── logout.php
│── connectDB.php
│── getdata.php
│── UsersLog.php
│── ManageUsers.php
│── Export_Excel.php
│── devices.php
│── header.php
│── dev_config.php
│── dev_up.php
│── ac_login.php
│── ac_update.php
│── manage_users_conf.php
│── manage_users_up.php
│── user_log_up.php
│── install.php
│── rfidattendance.sql
│── esp32_code/
│── README.md
```

---

## ⚙️ Setup Instructions

### 🔧 1. Clone Repository

```bash id="k2d9sj"
git clone https://github.com/your-username/rfid-attendance-system.git
cd rfid-attendance-system
```

### 🗃️ 2. Setup Database

* Open **phpMyAdmin**
* Create a database
* Import `rfidattendance.sql`

### ⚙️ 3. Configure Database

Edit `connectDB.php`:

```id="p9x3df"
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "your_database_name";
```

### 🌐 4. Run Project

* Start XAMPP/WAMP
* Place project in `htdocs`
* Open:
  👉 `http://localhost/rfid-attendance-system`

---

## 🔌 ESP32 Integration

* Upload code from `esp32_code/`
* Update WiFi credentials and server URL
* Connect RFID module (RC522) to ESP32
* Scan card → Data sent to server

---

## 📈 Future Enhancements

* 📱 Mobile app integration
* ☁️ Cloud database (Firebase/AWS)
* 🔔 Email/SMS alerts
* 📊 Advanced analytics dashboard

---

## 🤝 Contribution

Feel free to fork and improve this project.

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Biswajit Pattanaik**
Embedded Systems | IoT | Developer
