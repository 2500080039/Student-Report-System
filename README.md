# 🎓 CampusPulse – Student Report System

A role-based Student Report Management System developed using **React.js, Vite, JavaScript, JSX and CSS**.

CampusPulse helps educational institutions manage student academic information such as marks, grades, attendance and teacher remarks. It provides separate dashboards for Admin, Student and Parent.

## 🚀 Project Overview

The Student Report System simplifies academic record management through a user-friendly web application.

### Main Modules

1. **Admin Module**
   - Admin login
   - Add new student details
   - Enter student login credentials
   - Add subject-wise marks
   - Update attendance percentage
   - Add teacher remarks
   - View, search, edit and delete student records

2. **Student Module**
   - Student login
   - View subject-wise marks
   - View total marks and percentage
   - View grades
   - Check attendance
   - View teacher remarks

3. **Parent Module**
   - Parent login
   - View child's academic performance
   - Check marks and attendance
   - Monitor student progress

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| React.js | Building user interfaces |
| Vite | Development server and build tool |
| JSX | Writing UI structure |
| JavaScript | Application logic and functionality |
| CSS | Styling and responsive design |
| LocalStorage | Saving demo data in the browser |

## 📂 Project Structure

```text
student-report-system/
│
├── public/
│
├── src/
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
│
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ Installation and Setup

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open project folder

```bash
cd student-report-system
```

### Step 3: Install dependencies

```bash
npm install
```

### Step 4: Start development server

```bash
npm run dev
```

### Step 5: Open in browser

Open the local URL displayed in the terminal, usually:

```text
http://localhost:5173
```

## 🏗️ Build for Production

To create an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 💾 Data Storage

This project uses browser LocalStorage to save demo student information.

- `JSON.stringify()` converts JavaScript data into a string.
- `JSON.parse()` converts stored strings back into JavaScript data.

**Note:** LocalStorage is used for this frontend demonstration. It is not a secure production database or authentication system.

## 🌟 Key Features

- Role-based login for Admin, Student and Parent
- Student record management
- Subject-wise marks display
- Automatic total and percentage calculation
- Grade display
- Attendance management
- Teacher remarks
- Search and update student records
- Responsive user interface
- Browser-based demo data storage

## 🔮 Future Enhancements

- Backend database integration
- Secure user authentication
- PDF report generation
- Email and SMS notifications
- Academic performance graphs
- Cloud-based deployment

## 👨‍💻 Project Information

**Project Name:** CampusPulse – Student Report System

**Project Type:** Web Application

**Frontend:** React.js and CSS

**Build Tool:** Vite

**Storage:** Browser LocalStorage

## 🙏 Acknowledgement

This project was developed as part of our academic learning to understand React development, frontend technologies, user interface design and student report management.

# Thank You! 🎓
