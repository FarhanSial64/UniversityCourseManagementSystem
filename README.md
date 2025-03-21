## 📚 University Course Management System  

### **Overview**  
The **University Course Management System** is a **web-based platform** that streamlines the course registration process for students and administrators. It enables students to select courses while visualizing their schedules, ensuring time conflict resolution, real-time seat availability, and prerequisite tracking. Administrators can efficiently manage course offerings, student enrollments, and seat allocations.  

---

## 🚀 **Features**  

### **For Students**  
✔️ **Login System** – Secure authentication using roll numbers.  
✔️ **Interactive Weekly Schedule** – Visual timetable with real-time updates.  
✔️ **Real-Time Seat Availability** – No page refresh required for updated seat counts.  
✔️ **Course Filtering** – Search courses by department, time slots, availability, etc.  
✔️ **Prerequisite Tracking** – Alerts students about missing prerequisites.  
✔️ **Session Persistence** – Keeps selected courses even if the page reloads.  
✔️ **Notification for Seat Availability** *(Bonus Feature)* – Get notified when a seat becomes available.  

### **For Administrators**  
✔️ **Login System** – Secure authentication for admins.  
✔️ **Course Management** – Add, update, and remove courses, including prerequisites.  
✔️ **Student Enrollment Management** – Register or drop students from courses.  
✔️ **Seat Management** – Adjust seat availability dynamically.  
✔️ **Reports & Analytics** – Generate reports for:  
   - Students registered in a course  
   - Courses with available seats  
   - Students missing prerequisites  

---

## 🛠️ **Tech Stack**  

| **Technology** | **Usage** |
|--------------|-----------|
| **HTML, CSS, JavaScript (EJS)** | Frontend (Student & Admin Portal) |
| **Node.js & Express.js** | Backend API & Business Logic |
| **MongoDB** | Database for storing course and student data |
| **XAMPP (MySQL - optional)** | Local database testing |
| **Bootstrap & CSS** | UI Styling |
| **Git & GitHub** | Version Control |

---

## 🎯 **Installation & Setup**  

### **1️⃣ Clone the Repository**  

git clone https://github.com/FarhanSial64/UniversityCourseManagementSystem.git
cd UniversityCourseManagementSystem


### **2️⃣ Install Dependencies**  
npm install


### **3️⃣ Configure Environment Variables**  
Create a `.env` file in the project root and add the following:  

PORT=3000
MONGO_URI=mongodb://localhost:27017/university
SESSION_SECRET=your_secret_key


### **4️⃣ Start the Server**  

npm start

The server will start at `http://localhost:3000/`.

---

## 📌 **Usage**  

1️⃣ **Admin Login:** `/admin/login`  
2️⃣ **Student Login:** `/student/login`  
3️⃣ **View Schedule:** `/student/schedule`  
4️⃣ **Manage Courses (Admin):** `/admin/courses`  
5️⃣ **Seat Management:** `/admin/seats`  

---



---

## 🤝 **Contributing**  
1. Fork the repository.  
2. Create a new feature branch:  

   git checkout -b feature-name

3. Commit changes:  

   git commit -m "Add new feature"

4. Push to GitHub:  

   git push origin feature-name

5. Open a **Pull Request** on GitHub.

---

## 📜 **License**  
This project is open-source and available under the **MIT License**.

---

## 📩 **Contact**  
For questions or collaborations, reach out via GitHub or email -> farhansial64@gmail.com.

---

This README is **structured, professional, and detailed**. Let me know if you want to add any modifications! 🚀
