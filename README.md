# RaktSahyog:- Blood Donation Website
Here is the updated **README.md** with your project name changed to **RaktSahyog** instead of Hemova.

---

# 🩸 **RaktSahyog – Blood Donation & Hospital Management System**

**RaktSahyog** is a full-stack web application designed to connect **blood donors**, **hospitals**, and **blood donation camps** in a single fast and user-friendly platform.
It enables **donor registration**, **hospital onboarding**, **blood availability checking**, and **camp management**, all with a modern UI powered by **Tailwind CSS**.

---

## 🚀 **Features**

### 🧑‍🤝‍🧑 **Donor Module**

* Donor registration with full details
* Secure password hashing
* Login / Logout system
* Check blood availability across hospitals
* Clean, simple, responsive pages

### 🏥 **Hospital Module**

* Hospital registration & login
* Add, update, and manage blood stock
* Manage blood donation camps
* Protected dashboard (session-based access)
* Glass-effect Tailwind UI for hospital pages

### 🗂️ **Database**

Includes SQL dump containing:

* `signup` table (donors)
* `users` table (hospitals)

(SQL schema comes from your uploaded database dump.) 

---

## 🎨 **Tech Stack Used**

### **Frontend**

* HTML5
* CSS3
* Tailwind CSS 4.0
* FontAwesome icons
* Responsive modern UI (used in `hospitalRegister.html`) 

### **Backend**

* Core PHP
* MySQL / MariaDB
* Password hashing (bcrypt)
* Sessions & validations

### **Development Tools**

* Visual Studio Code
* XAMPP / PHPMyAdmin
* Tailwind CLI (configured using package.json) 

---

## ⚙️ **Installation & Setup**

### **1️⃣ Clone the repository**

```bash
git clone https://github.com/your-username/RaktSahyog.git
cd RaktSahyog
```

### **2️⃣ Install Tailwind (optional for UI changes)**

```bash
npm install
npm start
```

### **3️⃣ Import the Database**

* Open **PHPMyAdmin**
* Create database:

```
rakt_sahyog
```

* Import:

```
HemovaSQL.sql
```

### **4️⃣ Move the project to XAMPP**

Place the folder in:

```
C:/xampp/htdocs/RaktSahyog/
```

### **5️⃣ Run the project**

Open browser:

```
http://localhost/RaktSahyog/
```

---

## 📁 **Project Structure**

```
RaktSahyog/
│── index.php
│── hospitalRegister.php
│── hospitalLogin.php
│── check_blood_availability.php
│── manageCamps.php
│── delete_user.php
│── dbconnection.php
│── RaktSahyogSQL.sql / HemovaSQL.sql
│── /images (blood1.png, blood2.png, homeimg.jpg)
│── /src (Tailwind input/output)
│── package.json
```

---

## 🔒 **Security Features**

* Password hashing using `password_hash()`
* Database protection against SQL injection
* Session-based authentication
* Input validation & sanitization

---

## 📌 **Future Enhancements**

* Email OTP verification
* Admin panel
* Donor ID card / QR system
* Automated blood stock notification
* Live tracking of donation camps

---

## 🤝 **Contributing**

Pull requests are welcome. For major changes, please open an issue first to discuss your idea.




Just tell me!

