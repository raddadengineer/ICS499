# ICS499: Media Library Management System

This repository contains the final group project for ICS499, developed by Team Alpha. As the group leader, I coordinated the design, development, and deployment of this web-based media library management system.

## Project Overview

The Media Library Management System is a PHP and JavaScript-based web application that allows users to manage their personal collections of movies and music. The platform provides a user-friendly interface for adding, editing, viewing, and removing media items, with secure authentication and role-based access.

Site: https://ab-ics499.azurewebsites.net/

## Key Features

- **User Authentication:** Secure signup, login, and logout functionality for all users. Passwords are hashed and user sessions are managed to protect user data and prevent unauthorized access.
- **Media Management:** Add, edit, and remove movies and music from your personal library. Each media item can be customized with details such as title, genre, year, and cover image. Users can organize and update their collections easily.
- **Barcode Scanning:** Integrated barcode scanning (via QuaggaJS) for quick media entry. Users can scan the barcode of a DVD, Blu-ray, or CD to automatically retrieve and populate media information, streamlining the process of adding new items.
- **Responsive UI:** Modern, responsive design for desktop and mobile devices. The interface adapts to different screen sizes, ensuring a smooth experience whether on a computer, tablet, or smartphone.
- **Role-Based Access:** Admin and user roles for managing access to sensitive features. Admins have additional privileges such as managing user accounts and overseeing the entire media library, while regular users can manage only their own collections.
- **Database Integration:** Persistent storage of user and media data using MySQL. All changes are saved in real time, ensuring data consistency and reliability across sessions.
- **Error Handling:** User-friendly error messages and validation throughout the app. The system provides clear feedback for invalid inputs, failed operations, or system errors, helping users resolve issues quickly and efficiently.

## Main Functions

- **Add Media:** Users can add new movies or music to their library, either manually or by scanning a barcode.
- **Edit Media:** Update details for existing media items.
- **Delete Media:** Remove items from the library with confirmation prompts.
- **View Library:** Browse and search the entire media collection.
- **Manage Users:** Admins can manage user accounts and permissions.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript (including QuaggaJS for barcode scanning)
- **Backend:** PHP
- **Database:** MySQL
- **Deployment:** Azure Web Services

## Team and Leadership

This project was completed as a group effort for ICS499. As the group leader, I was responsible for project planning, task delegation, code reviews, and ensuring timely delivery. The collaborative effort resulted in a robust and user-friendly application.

## Getting Started

1. Clone the repository
2. Set up the database using the provided SQL scripts
3. Configure database connection settings in the PHP files
4. Deploy to your preferred web server or use the provided Azure deployment

---

For more details, see the source code and comments throughout the project.
