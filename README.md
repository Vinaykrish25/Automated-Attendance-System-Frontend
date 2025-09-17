# 🎓 Smart Attendance System – Frontend (React.js)

This is the **frontend** of the Smart Attendance System project, built using **React.js**.  
It provides a user-friendly interface for students and admins to interact with the automated attendance system.

🔗 **Live Demo (Frontend):** [See demo](https://automated-attendance-system-fronten.vercel.app/)

---

## 💻 Frontend Setup (React.js)

### 1. 📁 Install dependencies

```bash
cd frontend
npm install
npm install axios chart.js chartjs-plugin-datalabels file-saver html2canvas jspdf react-chartjs-2 react-heatmap-grid react-icons react-router-dom xlsx
```

### 2. 🚀 Run Frontend

```bash
npm start
```

### 📸 Screenshots

### 🏠 Home Page

![Home Page](../screenshots//HomePage.png)

---

### 🎓 Student Dashboard

![Student Dashboard](../screenshots/Student_Dashboard.png)

---

### 🔐 Admin Login Page

![Admin Login](../screenshots/Admin_Login.png)

---

### 📅 Attendance Records Table

![Attendance Records](../screenshots/Attendance_Records.png)

---

### 📊 Absences by Period (Bar Chart)

![Chart 1](../screenshots/Chart_1.png)

---

### 🧍 Single Student Attendance Proportions (Pie Chart)

![Chart 2](../screenshots/Chart_2.png)

---

### 👥 Absent Periods by Student (Bar Chart)

![Chart 3](../screenshots/Chart_3.png)

---

### 🧾 Attendance Composition per Student (Stacked Chart)

![Chart 4](../screenshots/Chart_4.png)

---

### 📈 Overall Attendance Trend (Line Chart)

![Chart 5](../screenshots/Chart_5.png)

---

### ✅ Project Structure (Frontend Only)

```
frontend
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── ...
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   │   ├── auth/
│   ├── redux/
│   ├── styles/
│   ├── api.js
│   ├── theme.js
│   └── App.js
└── package.json
```

### 🧠 Contributions

This frontend was developed with React.js to integrate seamlessly with the backend (Node.js + Express + MongoDB) and the Python-based face recognition module. It includes modern UI, chart visualizations, and responsive design.

```