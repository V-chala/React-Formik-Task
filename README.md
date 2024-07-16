# React-Formik-Task

# Book Data Management System

This is a simple CRUD application built with HTML, CSS, JavaScript, and React for managing book data. It allows users to perform Create, Read, Update, and Delete (CRUD) operations on book records. The application uses Formik for form validation and integrates with a backend API for data storage and retrieval.

## Technologies Used

- **HTML**: Used for structuring the web pages.
- **CSS**: Used for styling and layout.
- **JavaScript**: Used for implementing dynamic behavior on the client-side.
- **React**: Used for building a modular and scalable user interface.
- **Formik**: Used for form validation and handling in React.
- **Bootstrap**: Used for styling components and responsive design.
- **Axios**: Used for making HTTP requests to the backend API.

## Features

- Add new books with details such as title, author, ISBN number, and publication date.
- Edit existing book details, including updating author information.
- View a dashboard with key statistics and information about earnings, tasks, and pending requests.
- Delete books from the system.

## Backend API Integration

The application communicates with a backend API to perform CRUD operations on book data. The API endpoints are as follows:

- **POST /Formik-validation**: Add a new book.
- **GET /Formik-validation**: Retrieve all books.
- **GET /Formik-validation/:id**: Retrieve a specific book by ID.
- **PUT /Formik-validation/:id**: Update the details of a book.
- **DELETE /Formik-validation/:id**: Delete a book.
