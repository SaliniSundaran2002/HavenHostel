# 🌟 HavenHostel 🌟  
_A modern solution for efficient hostel management._

---

## 📖 About
HavenHostel is a comprehensive hostel management system built with **PHP**. It streamlines room allocation, mess billing, and food tracking, making hostel administration seamless and efficient. With an intuitive interface, it simplifies day-to-day tasks for both administrators and residents.

---

## 🚀 Features
✅ **Automated Room Allocation**  
Effortlessly assign rooms with zero manual errors.  

✅ **Mess Billing Management**  
Generate and manage bills with precision.  

✅ **Food Tracking**  
Optimize resources by monitoring food consumption.  

✅ **Attendance Marking**  
Mark and track the attendance of students for each day, ensuring accurate records.  

✅ **Student Mess Allotment**  
Assign students to specific mess slots (e.g., breakfast, lunch, dinner), track their meals, and monitor food preferences.  

✅ **User-Friendly Interface**  
Simplify operations with a sleek, intuitive UI.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  

---

## 📦 Installation

### Step 1: Install a Local Server
1. Download and install a local server stack like **XAMPP**, **WAMP**, or **MAMP**.  
   - **[Download XAMPP](https://www.apachefriends.org/index.html)**  
2. Start the **Apache** (PHP) and **MySQL** services.

### Step 2: Set Up the Project
1. Move the project folder (e.g., `HavenHostel`) to the `htdocs` directory:
   ```bash
   C:\xampp\htdocs\HavenHostel

2. Open `phpMyAdmin` by visiting `http://localhost/phpmyadmin` in your browser.
3. Create a new database (e.g., `hostel`).
4. Import the provided SQL file:
   - Go to the **Import** tab in phpMyAdmin.
   - Select the SQL file (e.g., `/database/hostel.sql`) from the project.
   - Click **Go** to import.

### Step 3: Configure the Project
1. Open the `config.php` file in the project directory.
2. Update the database connection details:
   ```php
   $host = 'localhost';
   $user = 'root';
   $password = ''; // Leave blank for XAMPP
   $database = 'hostel';
