# Student-Teacher Booking Appointment System

This repository contains the source code for a Student-Teacher Booking Appointment system, built with HTML, CSS, JavaScript, and Firebase. It enables students to efficiently book appointments with teachers online.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [WorkFlow](#workflow-diagram)

## Features

- **Student Interface:**
  - Search and view teacher profiles.
  - Book appointments with teachers.
  - Send messages to teachers.
  
- **Teacher Interface:**
  - Manage appointment schedules.
  - Accept or reject student appointments.
  - Receive and respond to student messages.

- **Admin Interface:**
  - Manage teacher profiles (add/update/delete).
  - Approve student registrations.
  - Monitor system activity and logs.

## Technologies Used

- Frontend:
  - HTML
  - CSS
  - JavaScript

- Backend:
  - Firebase Authentication
  - Firebase Firestore (Database)
  
## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/nitukumariyadav/student-teacher-booking-appointment-.git

 2.  Navigate into the project directory:
 cd student-teacher-booking-appointment

 ## usage

 # Admin Usage:

Log in to the admin panel.
Manage teacher profiles (add/update/delete).
Approve student registrations.
View system logs and activity.


# Teacher Usage:

Login
Navigate to the homepage.
Manage appointment schedules.
Approve/Cencal Appointments
View All Appointment
Logout 

# Student Usage:

Register 
Login
Navigate to the homepage.
Search for teachers and view their profiles.
Book appointments by selecting available slots.
Communicate with teachers through the messaging feature.

## SCREENSHOTS

![Home Page](image.png)
![Admin Home Page](image-1.png)
![Student Home Page](image-2.png)
![Teacher Home Page](image-3.png)

## contributing
Nitu Kumari

## workflow-diagram

+---Home Page------------------------------------------+
|Admin Login| Student Login|Registration| Teacher Login|
+---------------------------------------------------------+
|          Admin Module          |
+--------+-----------+-----------+
| Add    | Update    | delete | Approve|cencel   |
| Teacher| Teacher   | Students  |
+--------+-----------+-----------+
         |
         v
+--------+-----------+
|     Firestore DB     |
+--------+-----------+
         |
         v
+--------+-----------+
|      Teacher Module        |
+--------+-----------+-----------------------------------+
|    Logout    | Manage    |
|   Appointments     |view  Messages  | Schdule mannage| Logout|
+--------+-----------+-----------+
         |
         v
+--------+-----------+
|     Firebase DB     |
+--------+-----------+
         |
         v
+--------+-----------+
|      Student Module        |
+--------+-----------+-----------+
|       Search   |
|    Teachers       | Book Appt | Send Message| Logout|
+--------+-----------+-----------+



