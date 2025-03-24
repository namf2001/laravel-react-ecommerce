# Project Overview

## Introduction
This project is a web application built using a combination of PHP, TypeScript, JavaScript, and React. It leverages several frameworks and tools, including Laravel for the backend and Composer for dependency management.

## Technologies Used
- **PHP**: The primary language for backend development.
- **Laravel**: A PHP framework used for building the backend of the application.
- **TypeScript**: A superset of JavaScript used for type-safe frontend development.
- **JavaScript**: Used alongside TypeScript for frontend development.
- **React**: A JavaScript library for building user interfaces.
- **Composer**: A dependency manager for PHP.
- **NPM**: A package manager for JavaScript.

## Key Features
- **User Authentication**: Secure user authentication and authorization using Laravel and Spatie's Laravel Permission package.
- **Role Management**: Role-based access control with predefined roles such as Administrator, Vendor, and User.
- **Job Management**: Handling background jobs using Laravel's job queues.
- **Vendor Approval**: Functionality for approving vendors.
- **Product Management**: Features for selling and buying products.

## Project Structure
- **app/Models**: Contains the Eloquent models, including the `User` model.
- **database/migrations**: Contains the migration files for creating database tables.
- **database/seeders**: Contains the seeder files for populating the database with initial data.
- **app/Enums**: Contains the enumeration classes, such as `PermissionsEnum`.

## Setup Instructions
1. **Clone the repository**:
   ```sh
   git clone <repository-url>
   cd <repository-directory>
