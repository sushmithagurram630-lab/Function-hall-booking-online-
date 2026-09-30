# Function Hall Booking System

Complete beginner-friendly full-stack project:

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js + Express
- Database: MySQL
- Database driver: mysql2
- Authentication: bcryptjs
- API: REST-style JSON endpoints

## Features

1. Register
2. Login
3. Browse function halls
4. Select decoration
5. Select food package
6. Enter event date and guest count
7. Calculate total amount
8. Create booking
9. View my bookings
10. Cancel booking
11. Admin dashboard
12. Admin can add halls, decorations and food packages
13. Admin can update booking status

## Requirements

Install:

- Node.js 18+
- MySQL 8+
- VS Code (recommended)

## Step 1: Create the database

Open MySQL Workbench or MySQL command line.

Run:

    SOURCE database/schema.sql;

Or open `database/schema.sql`, copy its contents and execute it.

The database name is:

    function_hall_booking

## Step 2: Configure the backend

Open:

    backend/.env

Change DB_PASSWORD to your MySQL password.

Example:

    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=your_password
    DB_NAME=function_hall_booking
    PORT=5000

## Step 3: Install Node packages

Open a terminal in the `backend` folder:

    cd backend
    npm install

## Step 4: Start the server

Development mode:

    npm run dev

or:

    npm start

You should see:

    Function Hall Booking API running at http://localhost:5000

## Step 5: Open the application

Open:

    http://localhost:5000

Do not open index.html directly with file://.

## Demo admin

The SQL file creates an admin user:

Email:
    admin@functionhall.com

Password:
    Admin@123

For a real application, change the demo credentials.

## Important

This project uses Node.js + mysql2.

It does NOT use Java JDBC.

If your college specifically requires Java + JDBC, this project would need a Java backend instead.
