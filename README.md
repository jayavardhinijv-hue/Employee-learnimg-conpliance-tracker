Employee Learning & Compliance Tracker

📌 Overview

The Employee Learning & Compliance Tracker is a web-based application designed to manage employee training programs, compliance courses, task assignments, and learning progress.

The application provides separate login access for employees and administrators, allowing admins to manage courses and assignments while employees can access training materials, submit assignments, and track their progress.

🛠️ Technologies Used

Frontend

- React.js
- Vite
- JavaScript
- CSS

Backend

- PHP
- REST APIs

Database

- MySQL
- XAMPP

✨ Features

- Employee Login – Secure login for employees.
- Admin Login – Dedicated admin access to manage the application.
- Course Management – Create, update, and manage training courses.
- Task Assignment – Assign learning tasks to employees.
- Assignment Submission – Allow employees to submit completed assignments.
- Notifications – Notify employees about assigned tasks and updates.
- Compliance Tracking – Monitor employee training and compliance status.
- Progress Monitoring – Track employee learning progress and completion status.

📂 Project Structure

Employee-Learning-Compliance-Tracker/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   └── PHP API files
│
├── database/
│   └── employee_db.sql
│
└── README.md

⚙️ Installation & Setup

Prerequisites

Make sure the following software is installed:

- Node.js and npm
- XAMPP
- Git

Step 1: Clone the Repository

git clone <your-repository-url>

Step 2: Install and Configure XAMPP

1. Install XAMPP.
2. Copy the backend folder into the XAMPP "htdocs" directory.
3. Start Apache and MySQL from the XAMPP Control Panel.

Step 3: Import the Database

1. Open "http://localhost/phpmyadmin".
2. Create a database named "employee_db" (if it does not already exist).
3. Import the "employee_db.sql" file from the database folder.

Step 4: Configure Backend APIs

- Update the database connection settings in the PHP configuration file.
- Configure the frontend API base URL to point to your local PHP backend.

Step 5: Run the Frontend

Navigate to the frontend directory:

cd frontend

Install dependencies:

npm install

Start the development server:

npm run dev

Open the local URL displayed in the terminal to access the application.

👩‍💻 Author

Jayavardhini
