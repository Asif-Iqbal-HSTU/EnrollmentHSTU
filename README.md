# Smart Enrollment System (SES) for Hajee Mohammad Danesh Science and Technology University (HSTU)

## Introduction

The Smart Enrollment System (SES) is a web application designed to streamline and automate the enrollment process at Hajee Mohammad Danesh Science and Technology University (HSTU). By integrating all activities involved in the enrollment process into a single online system, SES aims to make the enrollment process more efficient, hassle-free, and time-saving compared to the traditional offline methods.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Admin Module](#admin-module)
- [Student Enrollment Module](#student-enrollment-module)
- [Technologies Used](#technologies-used)
- [Screenshots](#screenshots)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Features

- Online enrollment process
- Student login
- Admin management of student information and fees
- SSL Commerz payment gateway integration
- Real-time updates on enrollment status
- Detailed view of enrollment fees and status
- Efficient and time-saving compared to offline methods

## Requirements

- Option for student login
- View and update of enrollment-related fees by admin
- Upload and update student information by admin
- Smart payment system with multiple payment options (Bkash, Nagad, Rocket, SureCash, VisaCard, etc.)
- Contact option for application admin
- Admin dashboard to view students' enrollment status
- List of students with enrolled or pending status

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/awe-some-Guy/EnrollmentSystem_HSTU.git
    cd EnrollmentSystem_HSTU
    ```

2. Install dependencies:
    ```bash
    composer install
    npm install
    ```

3. Set up environment variables:
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```

4. Configure the `.env` file with your database and payment gateway settings.

5. Run migrations and seed the database:
    ```bash
    php artisan migrate --seed
    ```

6. Start the development server:
    ```bash
    php artisan serve
    ```

## Usage

### Admin Module

- View all student information
- Upload and update student details
- View and update enrollment fees
- Monitor students' enrollment status

### Student Enrollment Module

- Student login and access to enrollment page
- View enrollment-related fees
- Make payments through SSL Commerz gateway
- Complete enrollment process online

## Technologies Used

- Laravel
- Vue.js
- SSL Commerz payment gateway
- MySQL
- Bootstrap

## Screenshots

### Landing Page
![1](https://github.com/awe-some-Guy/EnrollmentSystem_HSTU/assets/40653155/ecb919dc-0e98-41ec-b26a-a93453b90431)
![4](https://github.com/awe-some-Guy/EnrollmentSystem_HSTU/assets/40653155/d0972e6f-526d-4c32-8e3c-da9ca32b656d)

### Student Dashboard
![8](https://github.com/awe-some-Guy/EnrollmentSystem_HSTU/assets/40653155/30ff710a-b4e2-46b7-b0f2-dcf27c27c73a)

### Payment Page
![10](https://github.com/awe-some-Guy/EnrollmentSystem_HSTU/assets/40653155/ef2114ae-c360-4746-8fb0-175d9a79c4ba)


## Contact

For any inquiries or feedback, please contact us at:
- Email: asif.iqbal.hstu@gmail.com

## Acknowledgements

- We would like to thank all the contributors and supporters of this project.
- Special thanks to the faculty and administration of HSTU for their continuous support.
