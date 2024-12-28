# UNILINK - Student Information System and Course Scheduling

![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Version](https://img.shields.io/badge/version-1.0.0-orange)

A subsystem of the UNILINK: Academic Community Web Application, designed to streamline student information management and enhance administrative processes.

![UNILINK Logo](unilink_logo.png)

## Project Overview

The UNILINK: Academic Community Web Application is an interactive, web-based platform designed specifically for academic institutions. Its primary goal is to enhance the management of student information, streamline course scheduling, and facilitate accurate grade viewing. Acting as a comprehensive Student Information System (SIS), UNILINK unites essential academic management tasks into a single, integrated platform.

This system offers significant improvements in operational efficiency, allowing administrative staff to reduce manual tasks and focus on core academic responsibilities. For students, it ensures accessibility and transparency in accessing academic records, schedules, and performance updates. The platform is built with a user-friendly interface, making it easy for students to interact with the system and stay informed about their academic progress.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Security](#security)
- [User Roles](#user-roles)
- [License](#license)

## Features

- **Secure Authentication System**

  - Role-based access control (Admin/Student)
  - Encrypted password protection
  - Session management

- **Student Portal**

  - Personal information management
  - Academic record viewing
  - Course registration
  - Document requests

- **Administrative Dashboard**
  - Student records management
  - Course management
  - Academic data administration
  - System monitoring

## Tech Stack

- **Frontend**

  - HTML5
  - CSS3 (Bootstrap 5.2.0)
  - JavaScript
  - Font Awesome 6.1.1

- **Backend**
  - PHP
  - MySQL Database

## Prerequisites

- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx)
- Modern web browser

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Khadalicioso/unilink_student_information_system.git
   ```

2. Configure your web server to point to the project directory

3. Import the database:

   - Create a new MySQL database
   - Import the SQL file from the `data` directory

4. Configure database connection:

   - Update the credentials in `DB_connection.php`

5. Access the system through your web browser

## Security

- Implements secure password hashing
- Protected against SQL injection
- Session-based authentication
- Input validation and sanitization

## User Roles

1. **Administrator**

   - Full system access
   - User management
   - System configuration

2. **Student**
   - Personal profile management
   - Academic information access
   - Document requests

## License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).
