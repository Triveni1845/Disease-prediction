# Disease Prediction System

## Overview

The Disease Prediction System is a web-based application developed using PHP and MySQL. The system helps users identify possible diseases based on selected symptoms and provides relevant disease information. It is designed to assist users in understanding potential health conditions through a simple and interactive interface.

## Features

* User Registration and Login
* Admin Login and Dashboard
* Symptom-Based Disease Prediction
* Disease Information Display
* User Management
* Disease Management
* Feedback Management
* Responsive User Interface

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

### Backend

* PHP

### Database

* MySQL

## Project Structure

```text
Disease-Prediction-System/
│
├── css/
├── js/
├── images/
├── database/
│   └── disease.sql
├── index.php
├── login.php
├── admin_login.php
├── result.php
└── other PHP files
```

## Installation and Setup

### Prerequisites

* XAMPP
* PHP
* MySQL
* Web Browser

### Steps to Run

1. Install XAMPP.
2. Copy the project folder to:

```text
C:\xampp\htdocs\
```

3. Start Apache and MySQL from the XAMPP Control Panel.
4. Open phpMyAdmin.
5. Create a database named:

```sql
disease
```

6. Import the SQL file:

```text
database/disease.sql
```

7. Open the project in your browser:

```text
http://localhost/Disease-Prediction-System-master
```

## User Roles

### Admin

The admin can:

* Add Diseases
* Edit Diseases
* Delete Diseases
* Manage Users
* View Feedback

### User

The user can:

* Register/Login
* Select Symptoms
* View Predicted Diseases
* Submit Feedback

## How It Works

1. User selects a body part.
2. User selects related symptoms.
3. The system analyzes the selected symptoms.
4. Disease data is fetched from the database.
5. The most relevant disease information is displayed.

## Future Enhancements

* Machine Learning-Based Prediction
* AI Chatbot Integration
* Email Notifications
* Doctor Recommendation System
* Mobile Application Support
* Disease Probability Scoring

## Author

**Triveni Patil**

MCA Student | Full Stack Developer

GitHub: https://github.com/Triveni1845

## License

This project is developed for educational and learning purposes.
