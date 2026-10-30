# Clinic Management System

A web-based clinic management system developed as a university project. The application provides basic functionality for managing clinic-related data, including users, patients, doctors, appointments, medical records, and categories.

## Tech Stack

- Node.js
- JavaScript
- MySQL
- Sequelize
- HTML
- CSS

## Features

- User authentication
- Patient management
- Doctor management
- Appointment management
- Medical record management
- Category management
- MySQL database integration
- Server-side routing and rendering

## Project Structure

```text
├── controllers/      # Application logic
├── models/           # Sequelize database models
├── views/            # HTML views
├── auth.js           # Authentication
├── koneksi.js        # Database connection
├── server.js         # Main server
├── package.json      # Dependencies and scripts
└── .env              # Environment variables (not included)
```

## Getting Started

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- [XAMPP](https://www.apachefriends.org/) or another MySQL server

### 1. Clone the repository

```bash
git clone <repository-url>
cd <project-folder>
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure the database

Start MySQL through XAMPP and create a MySQL database.

Create a `.env` file in the project root:

```env
DB_NAME=your_database_name
DB_USER=root
DB_PASS=
DB_HOST=localhost
DB_PORT=3306
```

### 4. Run the application

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## Notes

This project was originally developed as a university project and has been revisited for portfolio purposes.

The `.env` file and database credentials are intentionally excluded from the repository.

## License

This project is intended for educational and portfolio purposes.