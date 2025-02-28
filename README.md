# 📄 Credit-Based Document Scanning System  

## 🚀 Introduction  
The **Credit-Based Document Scanning System** is a secure platform designed for **document scanning and similarity detection**, integrated with a **credit-based access system**. Users receive **daily credits** for scanning documents, and an **intelligent matching system** detects similarities between uploaded documents and existing history.  

This project demonstrates expertise in **full-stack development**, **secure authentication**, and **efficient database management**.  

---

## 🔥 Key Features  

### 🟢 **User Features**  
✅ **Secure Login & Registration**  
✅ **Credit System**:  
   - Users receive **20 free credits every midnight**.  
   - Each **document scan costs 1 credit**.  
✅ **Upload & Manage Documents**  
✅ **Document Similarity Detection**:  
   - The system compares new uploads with existing **user history**.  
   - Displays **percentage match** if any document is similar.  
✅ **Track Document History**  
✅ **Request Additional Credits from Admin**  

### 🔴 **Admin Features**  
✅ **Approve or Reject Users**  
✅ **Manage User & Admin Roles**  
✅ **Monitor Credit Requests & Approve/Reject**  
✅ **View & Manage Uploaded Documents**  
✅ **Deactivate/Activate Users**  
✅ **Dashboard Insights**:  
   - **Total Users & Admins**  
   - **Total Documents Uploaded**  
   - **Pending Credit Requests**  
   - **Recent Activity Log**  

---

## 🛠️ Setup Instructions  

### 1️⃣ Install Dependencies  

npm install
## 2️⃣ Start the Backend Server
node server.js

## 3️⃣ Run the Frontend
Open login.html in VS Code and use the Live Server extension to preview.

## 🗄️ Database Setup (SQLite)
The project uses SQLite as the database.
After user registration, manually update the approved field in the users table to 1 for the first admin.
Admins can then manage users via the Admin Dashboard.

## 🎥 Demo Video  
[![Watch the demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://drive.google.com/file/d/1YcRffP0EzcT-Ogu-jM6nB82wet66Xfpv/view?usp=sharing)



## 🏗️ Tech Stack
## Frontend: HTML, CSS, JavaScript
## Backend: Node.js, Express.js
## Database: SQLite
## Storage: File system for document management
Authentication: bcrypt for password hashing

## 📩 Contact
For any queries, reach out at:
📧 Email: ayyappachowdarykandula@gmail.com
