# Book Management System

The Book Management System is a full-stack web application that allows users to manage a collection of books. It provides features such as user authentication, CRUD operations for books, and search functionality.

## Technologies Used

- **Frontend**:
  - React.js
  - HTML/CSS
  - Axios, Fetch (for API requests)
  
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose (for MongoDB ODM)

## Features

- **User Authentication**: Users can log in with their username and password.
- **Role-based Access Control**: Different users have different permissions based on their roles (admin or regular user).
- **Book Management**:
  - Admins can create, update, delete and read books(CRUD).
  - Regular users can view books and search for them.
- **Responsive Design**: The application is designed to work well on both desktop and mobile devices.

## Installation

```bash
1. Clone the repository:

git clone <repository-url>
cd bookapp

2. Install dependencies:

npm install mongodb cors express

3. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add environment variables for MongoDB connection, session secret, etc.

4. Start the server:

Move to the backend folder (cd bookapp/backend)
node server.js

5. Start the development server:

npm start

6. Access the application at `http://localhost:3000`.

## API Endpoints

- **GET /RetrAll**: Retrieve all books.
- **POST /Insertion**: Insert a new book.
- **POST /Updation**: Update an existing book.
- **GET /search**: Search for books.
- **POST /Deletion**: Delete a book.
- **POST /login**: User login.
- **POST /signup**: User signup.

## Folder Structure

- **src**: Contains the frontend React.js code.
- **public**: Contains static assets and the HTML template for the frontend.
- **backend**: Contains the backend Node.js code, including models and routes.
- **node_modules**: Contains project dependencies.

## Collections

- **book**: Stores information about books, including fields like `bid`, `title`, `author`, `genre`, and `year_published`.
- **student_credential**: Stores credentials for student users, including fields like `username` and `password`.
- **admin_credential**: Stores credentials for admin users, including fields like `username` and `password`.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).

