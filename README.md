# Employee Management System (EMS)

A web-based **Employee Management System** built using React.js. The application provides an organized interface for managing employee information and navigating between different sections of the system.

## Features

* User Login
* Dashboard
* Employee Management
* Add Employee
* View Employee Details
* Update Employee Information
* Delete Employee Records
* Client-side navigation
* Toast notifications for user actions
* Responsive and user-friendly interface

## Technologies Used

* **React.js** – Frontend development
* **JavaScript** – Application logic
* **HTML5** – Structure
* **CSS3** – Styling
* **React Router DOM** – Page navigation and routing
* **React Hot Toast** – Notifications
* **Vite** – Development and build tool
* **Git & GitHub** – Version control

## Project Structure

```text
EMS/
│
├── public/
│
├── src/
│   ├── assets/
│   │
│   ├── components/
│   │
│   ├── pages/
│   │   ├── LoginLanding.jsx
│   │   ├── Layout.jsx
│   │   ├── Dashboard.jsx
│   │   └── ...
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── ...
│
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project folder

```bash
cd EMS
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

The application will be available at the local URL provided by Vite, usually:

```text
http://localhost:5173
```

## Application Flow

```text
Login Page
     ↓
Authentication
     ↓
Dashboard
     ↓
Employee Management
     ↓
Add / View / Update / Delete Employees
```

## Routing

The application uses **React Router DOM** for navigation between different pages.

The main application flow includes:

* Login page
* Dashboard
* Employee management pages
* Other application pages

Protected routes can be used to prevent unauthorized users from accessing the main application.

## Notifications

**React Hot Toast** is used to display feedback messages to users.

Examples include:

* Successful login
* Employee added successfully
* Employee updated successfully
* Employee deleted successfully
* Invalid credentials
* Validation errors

## Future Enhancements

* Backend API integration
* Database integration
* Role-based authentication
* Admin and employee roles
* Employee attendance management
* Leave management
* Payroll management
* Advanced search and filtering
* Employee profile management
* Improved responsive design

## Learning Outcomes

This project helped in understanding and implementing:

* React.js fundamentals
* Components and props
* React Hooks
* State management
* React Router
* CRUD operations
* Form handling
* Authentication
* Protected routes
* Toast notifications
* Vite-based React development
* Git and GitHub

## Author

**Anuskha Anand**

---

⭐ If you found this project useful, consider giving the repository a star!
