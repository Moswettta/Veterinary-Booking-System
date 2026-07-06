# Veterinary Booking System

## Overview

The Veterinary Booking System is a web-based application developed using PHP and MySQL to simplify the management of veterinary appointments. The system enables pet owners to book appointments online while allowing receptionists, veterinarians, and administrators to efficiently manage bookings, users, and reports.

---

## Features

### Pet Owner
- User registration and login
- Manage pet profiles
- Book veterinary appointments
- View appointment history
- Update personal profile

### Receptionist
- View and manage appointments
- Access pet owner profiles
- Generate reports
- Manage personal profile

### Veterinarian
- View assigned clients
- Manage appointment queue
- Set availability schedule
- Update profile

### Administrator
- Dashboard with system overview
- Manage users
- Assign veterinarians to appointments
- Configure system settings
- Generate reports

---

## Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- Bootstrap
- XAMPP/WAMP/LAMP

---

## Project Structure

```
veterinary-booking-system/
│
├── admin/
├── config/
├── db/
├── pet_owner/
├── receptionist/
├── veterinarian/
├── login.php
├── logout.php
├── index.php
└── README.md
```

---

## Installation

### Requirements

- PHP 8.x or later
- MySQL
- Apache Server
- XAMPP/WAMP/LAMP

### Steps

1. Clone or download the project.

2. Copy the project folder into your web server directory.

Example (XAMPP):

```
htdocs/
```

3. Create a MySQL database.

Example:

```
vet_booking_db
```

4. Import the SQL file located in:

```
db/vet_booking_db (4).sql
```

5. Configure the database connection inside:

```
config/db.php
```

Update:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "vet_booking_db";
```

6. Start Apache and MySQL.

7. Open your browser and visit:

```
http://localhost/veterinary-booking-system/
```

---

## User Roles

The system supports four user roles:

- Administrator
- Receptionist
- Veterinarian
- Pet Owner

Each role has its own dashboard and permissions.

---

## System Modules

- Authentication
- Appointment Booking
- Pet Management
- Veterinarian Assignment
- Availability Scheduling
- Queue Management
- Reports
- User Management
- Profile Management

---

## Database

The database includes tables for:

- Users
- Pets
- Appointments
- Veterinarians
- Availability
- Roles
- System configurations

---

## Security Features

- Session-based authentication
- Role-based access control
- SQL prepared statements
- Input validation
- Protected dashboards

---

## Future Improvements

- Email notifications
- SMS reminders
- MPesa payment integration
- Online consultation
- Medical history records
- Prescription management
- File uploads
- Analytics dashboard

---

## Author

**Benjamin Maosa Mosweta**

BBIT Graduate

ICT Support | Web Developer | System Developer

Email: benjaminmosweta@gmail.com

LinkedIn:
https://www.linkedin.com/in/benjamin-maosa-860157247/

---

## License

This project was developed for educational and academic purposes. You are free to modify and improve it for learning purposes.

---

## Screenshots

You can include screenshots here:

- Login Page
- Admin Dashboard
- Pet Owner Dashboard
- Receptionist Dashboard
- Veterinarian Dashboard
- Appointment Booking Page

---

## Acknowledgements

Special thanks to everyone who contributed ideas, testing, and feedback during the development of this Veterinary Booking System.
