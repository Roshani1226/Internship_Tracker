Digital Internship Application Tracker

📌 Project Overview

The **Digital Internship Application Tracker** is a desktop-based application developed using **Python, Tkinter, and MySQL**. It helps students manage and track their internship applications in one place.

Instead of maintaining internship details manually in notebooks or spreadsheets, students can store company information, internship roles, application dates, deadlines, interview dates, stipend details, and application status in a MySQL database.

---

🎯 Objectives

* To provide an easy way to manage internship applications.
* To store internship application data securely in MySQL.
* To track the status of each internship application.
* To manage application deadlines and interview dates.
* To search, update, and delete internship records easily.
* To provide a simple and user-friendly graphical interface.

---

✨ Features

1. Add Internship Application

Users can add details such as:

* Company Name
* Internship Role
* Location
* Internship Type
* Application Date
* Application Deadline
* Status
* Interview Date
* Stipend
* Duration
* Website
* Notes

2. View Applications

All saved internship applications are displayed in a table using Tkinter's Treeview.

3. Search Applications

Users can search for internship applications using relevant information such as company name or internship role.

4. Update Application

Existing internship application details can be modified whenever required.

5. Delete Application

Unwanted internship application records can be deleted from the database.

6. Application Status Tracking

The application status can be tracked using:

* Applied
* Shortlisted
* Interview
* Selected
* Rejected
* Withdrawn

7. Dashboard

The dashboard displays important application statistics such as:

* Total Applications
* Applied Applications
* Shortlisted Applications
* Selected Applications

8. MySQL Database

All internship application records are stored in a MySQL database.

9. User-Friendly GUI

The application uses **Tkinter** to provide a simple graphical user interface.

---

🛠️ Technologies Used

| Technology      | Purpose                    |
| --------------- | -------------------------- |
| Python          | Main programming language  |
| Tkinter         | Graphical User Interface   |
| MySQL           | Database management        |
| MySQL Connector | Connects Python with MySQL |
| VS Code         | Development environment    |

---

📂 Project Structure

```text
Digital_Internship_Tracker/
│
├── internship_tracker.py
├── internship_data.sql
└── README.md
```

---

💻 System Requirements

Before running the project, install:

* Python 3.x
* MySQL Server
* MySQL Workbench or MySQL Command Line Client
* Visual Studio Code (recommended)

---

📦 Required Python Library

Install the MySQL Connector using:

```bash
python -m pip install mysql-connector-python
```

To check whether it is installed:

```bash
python -c "import mysql.connector; print('MySQL Connector is working')"
```

---

🗄️ Database Setup

The project uses a MySQL database named:

```text
internship_tracker
```

The application can automatically create the database and required table.

The main table is:

```text
applications
```

Database Fields

| Field            | Description                |
| ---------------- | -------------------------- |
| id               | Unique application ID      |
| company_name     | Name of the company        |
| internship_role  | Internship position        |
| location         | Internship location        |
| internship_type  | Online/Offline/Hybrid      |
| application_date | Date of application        |
| deadline         | Application deadline       |
| status           | Current application status |
| interview_date   | Interview date             |
| stipend          | Internship stipend         |
| duration         | Internship duration        |
| website          | Company/internship website |
| notes            | Additional information     |

---

🔐 MySQL Configuration

Open `internship_tracker.py` and update the MySQL password:

```python
DB_HOST = "localhost"
DB_USER = "root"
DB_PASSWORD = "YOUR_MYSQL_PASSWORD"
DB_NAME = "internship_tracker"
```

Replace:

```text
YOUR_MYSQL_PASSWORD
```

with your actual MySQL root password.

For example:

```python
DB_PASSWORD = "12345"
```

**Do not upload your real MySQL password to a public GitHub repository.**

---

▶️ How to Run the Project

Step 1: Open the Project

Open the project folder in VS Code.

Step 2: Open Terminal

In VS Code, select:

```text
Terminal → New Terminal
```

Step 3: Install MySQL Connector

Run:

```bash
python -m pip install mysql-connector-python
```

Step 4: Check MySQL

Make sure the MySQL server is running.

Step 5: Run the Python Program

Run:

```bash
python internship_tracker.py
```

The application GUI will open.

---

🔄 Working of the Project

```text
Start Application
       ↓
Connect to MySQL
       ↓
Create Database/Table
       ↓
Open Tkinter GUI
       ↓
Add Internship Details
       ↓
Save Data in MySQL
       ↓
View / Search Applications
       ↓
Update / Delete Records
       ↓
Track Application Status
       ↓
Exit Application
```

---

📊 Application Status Flow

```text
Applied
   ↓
Shortlisted
   ↓
Interview
   ↓
Selected
```

An application may also move to:

```text
Applied → Rejected
```

or

```text
Applied → Withdrawn
```

---

🎓 Project Benefits

* Saves time in managing internship applications.
* Reduces the need for manual record keeping.
* Keeps all internship information organized.
* Makes it easy to track application progress.
* Helps students remember application deadlines and interviews.
* Provides centralized data storage using MySQL.
* Provides a simple graphical interface for beginners.

---

🔮 Future Scope

The project can be improved by adding:

* Student login and registration.
* Email notifications for deadlines.
* Automatic deadline reminders.
* Resume upload functionality.
* Internship search and filtering.
* Graphical reports and charts.
* Cloud database support.
* Export applications to Excel/PDF.
* Web-based version of the application.
* Mobile application support.

---

👩‍💻 Developer

**Roshani Patil**

**Course:** B.Tech – Computer Technology

**Project:** Digital Internship Application Tracker
