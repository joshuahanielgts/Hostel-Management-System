# 🏨 Hostel Management System - Installation Guide

Follow these simple steps to set up the **Hostel Management System** on your local machine using XAMPP.

---

## 🔧 Installation & Configuration Steps

### 📁 Step 1: Download & Extract
- Download the project ZIP file to your computer.
- Unzip the file to any location on your system.

### 📂 Step 2: Project Folder Setup
- Locate the **`hostel`** folder inside the unzipped files.
- Move the entire **`hostel`** folder to the following directory:  
  `C:/xampp/htdocs/`

> 📌 This step is important to run the project locally using XAMPP.

### 🛠️ Step 3: Database Configuration

1. Open **XAMPP** and start **Apache** and **MySQL** services.
2. Open your browser and navigate to:  
   `http://localhost/phpmyadmin`
3. Create a new database named **`hostel`**.
4. Import the SQL file:
   - Click on the **hostel** database.
   - Go to the **Import** tab.
   - Select the file named **`hostel.sql`** from the project folder.
   - Click **Go** to import.

---

## 🌐 Launch the Application

Open your browser and go to:  
👉 `http://localhost/hostel/`  
You should now see the homepage of the Hostel Management System.

---

## 🔐 Login Credentials

### 👨‍💼 Admin Login
- **Username:** `admin`  
- **Password:** `Test@1234`

### 👤 User Login
- **Username:** `test@gmail.com`  
- **Password:** `Test@123`  
*Alternatively, you can register a new user directly through the system.*

---

## 📬 Need Help?

If you run into any issues during setup, feel free to reach out. Happy coding! 😊
