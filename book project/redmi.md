# Book Project API

This is a simple RESTful API for managing a collection of books, built with Node.js, Express, and MongoDB. It provides endpoints to perform CRUD (Create, Read, Update, Delete) operations on books.

## Features

-   Get a list of all books.
-   Get a single book by its unique ID.
-   Add a new book to the collection.
-   Update the details of an existing book.
-   Remove a book from the collection.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need to have Node.js and npm (or yarn) installed on your machine. You also need access to a MongoDB database (either local or cloud-based).

### Installation

1.  Clone the repository:
    ```sh
    git clone https://your-repository-url/book-project.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd book-project
    ```
3.  Install the dependencies:
    ```sh
    npm install
    ```
4.  Create a `.env` file in the root directory and add your MongoDB connection string:
    ```
    MONGO_URI=your_mongodb_connection_string
    ```

### Running the Application

To start the server, run the following command:

```sh
npm start
```

The server will start, and by default, it should be running on a specified port (e.g., `http://localhost:3000`).

## API Endpoints

The following are the available endpoints for interacting with the API.

### Get All Books

-   **Method**: `GET`
-   **Endpoint**: `/api/books`
-   **Description**: Retrieves a list of all books in the database.
-   **Success Response (200 OK)**:
    ```json
    [
      {
        "_id": "60d5ec49f72e9e1f8c4b2a1b",
        "title": "The Great Gatsby",
        "author": "F. Scott Fitzgerald",
        "price": 10.99,
        "inStock": true
      }
    ]
    ```

### Get Book by ID

-   **Method**: `GET`
-   **Endpoint**: `/api/books/:id`
-   **Description**: Retrieves a single book by its ID.

### Create a New Book

-   **Method**: `POST`
-   **Endpoint**: `/api/books`
-   **Description**: Adds a new book to the database.
-   **Request Body**:
    ```json
    {
      "title": "New Book Title",
      "author": "Author Name",
      "price": 19.99,
      "inStock": true
    }
    ```

### Update a Book

-   **Method**: `PUT`
-   **Endpoint**: `/api/books/:id`
-   **Description**: Updates an existing book's information.

### Delete a Book

-   **Method**: `DELETE`
-   **Endpoint**: `/api/books/:id`
-   **Description**: Deletes a book from the database.

## Technologies Used

-   **Node.js**: JavaScript runtime environment.
-   **Express.js**: Web framework for Node.js.
-   **MongoDB**: NoSQL database.
-   **Mongoose**: Object Data Modeling (ODM) library for MongoDB.