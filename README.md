# AquaFlow – Smart Water Issue Monitoring and Management System

## 1. Project Overview

AquaFlow is a desktop-based Smart Water Issue Monitoring and Management System developed using Python, Tkinter, and MySQL.

The system is designed to help monitor water availability across buildings, report water-related issues, manage complaints, and communicate important water supply updates.

## 2. Project Objectives

- Monitor water availability across different buildings.
- Allow building captains to submit water-related complaints.
- Enable administrators to manage and respond to complaints.
- Provide updates on water supply conditions.
- Improve communication between building captains and administrators.
- Maintain organised records of water-related issues.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Tkinter | Desktop graphical user interface |
| MySQL | Database management |
| MySQL Connector | Python–MySQL connectivity |
| python-dotenv | Secure database configuration |

## 4. Main Features

- **Login System:** Secure login for different user roles.
- **Admin Dashboard:** Manage water-related complaints and system information.
- **Building Captain Dashboard:** Submit and monitor water complaints.
- **Complaint Management:** Track complaints through Pending, In Progress, and Resolved statuses.
- **Water Status Monitoring:** Monitor water availability across 12 buildings.
- **Announcements:** Share important water supply information.
- **Database Integration:** Store and retrieve application information using MySQL.

## 5. Buildings Covered

The system covers 12 buildings:

1. Khandroling
2. Tshogyleling
3. Ghadenling
4. Pemaling
5. Dekiling
6. Sherabling
7. Karmaling
8. Gakiling
9. Academic Block
10. Prayer Hall
11. Counselling Block
12. Library Block

## 6. Project Structure

```text
Smart_Water_System/
│
├── main.py
├── database.py
├── admin_dashboard.py
├── student_dashboard.py
├── setup_passwords.py
├── test_database.py
├── .gitignore
├── .env
└── README.md
```

**Note:** The `.env` file contains local database credentials and is not uploaded to GitHub.

## 7. Installation and Setup

### Requirements

- Python 3.x
- MySQL Server
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/Seldon-45/AquaFlow-Smart-Water-Management-System.git
```

### Step 2: Open the Project Folder

```bash
cd AquaFlow-Smart-Water-Management-System
```

### Step 3: Install Dependencies

```bash
python -m pip install mysql-connector-python python-dotenv
```

### Step 4: Configure the Database

Create the MySQL database and required tables using the project's database setup.

Create a `.env` file in the project folder and configure your local database credentials:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_mysql_password
DB_NAME=smart_water_db
```

Replace the example password with your own MySQL password.

### Step 5: Run the Application

```bash
python main.py
```

## 8. User Roles

The application supports two user roles:

- **Admin:** Responsible for managing complaints, monitoring water status, and handling system information.
- **Building Captain:** Responsible for reporting water-related issues and viewing complaint information.

## 9. Database

The application uses MySQL to store and manage system information, including user accounts, buildings, complaints, water status, announcements, and complaint updates.

## 10. Developer

**Project Name:** AquaFlow – Smart Water Issue Monitoring and Management System

**Programming Language:** Python

**Database:** MySQL

---

*Developed as an academic project to support more organised water issue monitoring and management.*