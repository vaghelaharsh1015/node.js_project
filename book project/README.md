# Book Project

A complete Node.js book management application built with Express, MongoDB, Mongoose, and EJS. This project is designed to be easy to read, extend, and publish on GitHub as a portfolio or learning project.

## What this project does

This application lets users manage a list of books with a browser interface:
- Add new books with title, author, and price
- Edit existing book records
- Delete books
- View all books in a table

It also includes a small REST API for book data under `/api/books`.

## Why it is useful

This project demonstrates core full-stack web development concepts:
- Server-side development with **Node.js** and **Express**
- Data persistence using **MongoDB** and **Mongoose**
- MVC-style structure with models, controllers, and routes
- A simple view layer using **EJS templates**
- Form handling, validation, and error handling

## Benefits and advantages

- **Easy to understand:** clean folder structure and readable code
- **Practical CRUD app:** covers create, read, update, delete book records
- **Ready for GitHub:** good fit for a portfolio repository README
- **Extensible:** simple to add authentication, search, pagination, or extra APIs
- **Real database storage:** uses MongoDB instead of in-memory data
- **Modern stack:** works with current Express and Mongoose versions

## Software used

- Node.js
- npm
- Express
- MongoDB
- Mongoose
- EJS
- dotenv
- nodemon (development)
- Visual Studio Code or any code editor

## Project structure

- `server.js` — application entry point and route definitions
- `config/db.js` — MongoDB connection setup
- `models/Book.js` — Mongoose schema for book data
- `controllers/bookController.js` — API controller logic for books
- `routes/bookRotes.js` — API routes for book operations
- `views/index.ejs` — EJS view template for the UI
- `package.json` — dependency list and project metadata

## How the flow works

1. User opens the application in a browser at `/`
2. Express handles the request in `server.js`
3. The route queries the `Book` model using Mongoose
4. Data is fetched from MongoDB via `config/db.js`
5. The server renders `views/index.ejs` with the book list
6. When the user submits forms, Express parses the request body
7. The application creates, updates, or deletes book records
8. The page reloads to show the updated book list

## How to use this project

1. Clone or download the repository
2. Install dependencies:

\`\`\`bash
npm install
\`\`\`

3. Create a `.env` file in the project root with your MongoDB connection string:

\`\`\`env
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/mydatabase?retryWrites=true&w=majority
PORT=5000
\`\`\`

4. Start the server:

\`\`\`bash
node server.js
\`\`\`

5. Open a browser and go to:

\`\`\`text
http://localhost:5000
\`\`\`

6. Use the form to add books, edit them, or delete them.

## API endpoints

- `GET /api/books` — retrieve all books
- `GET /api/books/:id` — retrieve one book
- `POST /api/books` — create a new book

> Note: The UI routes are implemented directly in `server.js` and include `/add-book`, `/edit-book/:id`, `/delete-book/:id`, and `/edit-ui/:id`.

## How to show it on GitHub

- Use this file (`redmi.md`) as the repository README content for GitHub display.
- Make sure the repository contains the project files and a `.gitignore` file if needed.
- Add a project description and tags when creating the GitHub repository.
- Commit the code and push to GitHub to publish it.

## Reference video

Watch the demo video here:

https://drive.google.com/file/d/1BybyU7jZZfYEWqsBWLAGWyIl4zL58u4E/view?usp=sharing

## License

MIT# Book Project

A complete Node.js book management application built with Express, MongoDB, Mongoose, and EJS. This project is designed to be easy to read, extend, and publish on GitHub as a portfolio or learning project.

## What this project does

This application lets users manage a list of books with a browser interface:
- Add new books with title, author, and price
- Edit existing book records
- Delete books
- View all books in a table

It also includes a small REST API for book data under `/api/books`.

## Why it is useful

This project demonstrates core full-stack web development concepts:
- Server-side development with **Node.js** and **Express**
- Data persistence using **MongoDB** and **Mongoose**
- MVC-style structure with models, controllers, and routes
- A simple view layer using **EJS templates**
- Form handling, validation, and error handling

## Benefits and advantages

- **Easy to understand:** clean folder structure and readable code
- **Practical CRUD app:** covers create, read, update, delete book records
- **Ready for GitHub:** good fit for a portfolio repository README
- **Extensible:** simple to add authentication, search, pagination, or extra APIs
- **Real database storage:** uses MongoDB instead of in-memory data
- **Modern stack:** works with current Express and Mongoose versions

## Software used

- Node.js
- npm
- Express
- MongoDB
- Mongoose
- EJS
- dotenv
- nodemon (development)
- Visual Studio Code or any code editor

## Project structure

- `server.js` — application entry point and route definitions
- `config/db.js` — MongoDB connection setup
- `models/Book.js` — Mongoose schema for book data
- `controllers/bookController.js` — API controller logic for books
- `routes/bookRotes.js` — API routes for book operations
- `views/index.ejs` — EJS view template for the UI
- `package.json` — dependency list and project metadata

## How the flow works

1. User opens the application in a browser at `/`
2. Express handles the request in `server.js`
3. The route queries the `Book` model using Mongoose
4. Data is fetched from MongoDB via `config/db.js`
5. The server renders `views/index.ejs` with the book list
6. When the user submits forms, Express parses the request body
7. The application creates, updates, or deletes book records
8. The page reloads to show the updated book list

## How to use this project

1. Clone or download the repository
2. Install dependencies:

\`\`\`bash
npm install
\`\`\`

3. Create a `.env` file in the project root with your MongoDB connection string:

\`\`\`env
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/mydatabase?retryWrites=true&w=majority
PORT=5000
\`\`\`

4. Start the server:

\`\`\`bash
node server.js
\`\`\`

5. Open a browser and go to:

\`\`\`text
http://localhost:5000
\`\`\`

6. Use the form to add books, edit them, or delete them.

## API endpoints

- `GET /api/books` — retrieve all books
- `GET /api/books/:id` — retrieve one book
- `POST /api/books` — create a new book

> Note: The UI routes are implemented directly in `server.js` and include `/add-book`, `/edit-book/:id`, `/delete-book/:id`, and `/edit-ui/:id`.

## How to show it on GitHub

- Use this file (`redmi.md`) as the repository README content for GitHub display.
- Make sure the repository contains the project files and a `.gitignore` file if needed.
- Add a project description and tags when creating the GitHub repository.
- Commit the code and push to GitHub to publish it.

## Reference video

Watch the demo video here:

https://drive.google.com/file/d/1BybyU7jZZfYEWqsBWLAGWyIl4zL58u4E/view?usp=sharing

## License

MIT# Book Project

A complete Node.js book management application built with Express, MongoDB, Mongoose, and EJS. This project is designed to be easy to read, extend, and publish on GitHub as a portfolio or learning project.

## What this project does

This application lets users manage a list of books with a browser interface:
- Add new books with title, author, and price
- Edit existing book records
- Delete books
- View all books in a table

It also includes a small REST API for book data under `/api/books`.

## Why it is useful

This project demonstrates core full-stack web development concepts:
- Server-side development with **Node.js** and **Express**
- Data persistence using **MongoDB** and **Mongoose**
- MVC-style structure with models, controllers, and routes
- A simple view layer using **EJS templates**
- Form handling, validation, and error handling

## Benefits and advantages

- **Easy to understand:** clean folder structure and readable code
- **Practical CRUD app:** covers create, read, update, delete book records
- **Ready for GitHub:** good fit for a portfolio repository README
- **Extensible:** simple to add authentication, search, pagination, or extra APIs
- **Real database storage:** uses MongoDB instead of in-memory data
- **Modern stack:** works with current Express and Mongoose versions

## Software used

- Node.js
- npm
- Express
- MongoDB
- Mongoose
- EJS
- dotenv
- nodemon (development)
- Visual Studio Code or any code editor

## Project structure

- `server.js` — application entry point and route definitions
- `config/db.js` — MongoDB connection setup
- `models/Book.js` — Mongoose schema for book data
- `controllers/bookController.js` — API controller logic for books
- `routes/bookRotes.js` — API routes for book operations
- `views/index.ejs` — EJS view template for the UI
- `package.json` — dependency list and project metadata

## How the flow works

1. User opens the application in a browser at `/`
2. Express handles the request in `server.js`
3. The route queries the `Book` model using Mongoose
4. Data is fetched from MongoDB via `config/db.js`
5. The server renders `views/index.ejs` with the book list
6. When the user submits forms, Express parses the request body
7. The application creates, updates, or deletes book records
8. The page reloads to show the updated book list

## How to use this project

1. Clone or download the repository
2. Install dependencies:

\`\`\`bash
npm install
\`\`\`

3. Create a `.env` file in the project root with your MongoDB connection string:

\`\`\`env
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/mydatabase?retryWrites=true&w=majority
PORT=5000
\`\`\`

4. Start the server:

\`\`\`bash
node server.js
\`\`\`

5. Open a browser and go to:

\`\`\`text
http://localhost:5000
\`\`\`

6. Use the form to add books, edit them, or delete them.

## API endpoints

- `GET /api/books` — retrieve all books
- `GET /api/books/:id` — retrieve one book
- `POST /api/books` — create a new book

> Note: The UI routes are implemented directly in `server.js` and include `/add-book`, `/edit-book/:id`, `/delete-book/:id`, and `/edit-ui/:id`.

## How to show it on GitHub

- Use this file (`redmi.md`) as the repository README content for GitHub display.
- Make sure the repository contains the project files and a `.gitignore` file if needed.
- Add a project description and tags when creating the GitHub repository.
- Commit the code and push to GitHub to publish it.

## Reference video

Watch the demo video here:

https://drive.google.com/file/d/1BybyU7jZZfYEWqsBWLAGWyIl4zL58u4E/view?usp=sharing

## License

MIT# Book Project

A complete Node.js book management application built with Express, MongoDB, Mongoose, and EJS. This project is designed to be easy to read, extend, and publish on GitHub as a portfolio or learning project.

## What this project does

This application lets users manage a list of books with a browser interface:
- Add new books with title, author, and price
- Edit existing book records
- Delete books
- View all books in a table

It also includes a small REST API for book data under `/api/books`.

## Why it is useful

This project demonstrates core full-stack web development concepts:
- Server-side development with **Node.js** and **Express**
- Data persistence using **MongoDB** and **Mongoose**
- MVC-style structure with models, controllers, and routes
- A simple view layer using **EJS templates**
- Form handling, validation, and error handling

## Benefits and advantages

- **Easy to understand:** clean folder structure and readable code
- **Practical CRUD app:** covers create, read, update, delete book records
- **Ready for GitHub:** good fit for a portfolio repository README
- **Extensible:** simple to add authentication, search, pagination, or extra APIs
- **Real database storage:** uses MongoDB instead of in-memory data
- **Modern stack:** works with current Express and Mongoose versions

## Software used

- Node.js
- npm
- Express
- MongoDB
- Mongoose
- EJS
- dotenv
- nodemon (development)
- Visual Studio Code or any code editor

## Project structure

- `server.js` — application entry point and route definitions
- `config/db.js` — MongoDB connection setup
- `models/Book.js` — Mongoose schema for book data
- `controllers/bookController.js` — API controller logic for books
- `routes/bookRotes.js` — API routes for book operations
- `views/index.ejs` — EJS view template for the UI
- `package.json` — dependency list and project metadata

## How the flow works

1. User opens the application in a browser at `/`
2. Express handles the request in `server.js`
3. The route queries the `Book` model using Mongoose
4. Data is fetched from MongoDB via `config/db.js`
5. The server renders `views/index.ejs` with the book list
6. When the user submits forms, Express parses the request body
7. The application creates, updates, or deletes book records
8. The page reloads to show the updated book list

## How to use this project

1. Clone or download the repository
2. Install dependencies:

\`\`\`bash
npm install
\`\`\`

3. Create a `.env` file in the project root with your MongoDB connection string:

\`\`\`env
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/mydatabase?retryWrites=true&w=majority
PORT=5000
\`\`\`

4. Start the server:

\`\`\`bash
node server.js
\`\`\`

5. Open a browser and go to:

\`\`\`text
http://localhost:5000
\`\`\`

6. Use the form to add books, edit them, or delete them.

## API endpoints

- `GET /api/books` — retrieve all books
- `GET /api/books/:id` — retrieve one book
- `POST /api/books` — create a new book

> Note: The UI routes are implemented directly in `server.js` and include `/add-book`, `/edit-book/:id`, `/delete-book/:id`, and `/edit-ui/:id`.

## How to show it on GitHub

- Use this file (`redmi.md`) as the repository README content for GitHub display.
- Make sure the repository contains the project files and a `.gitignore` file if needed.
- Add a project description and tags when creating the GitHub repository.
- Commit the code and push to GitHub to publish it.

## Reference video

Watch the demo video here:

https://drive.google.com/file/d/1BybyU7jZZfYEWqsBWLAGWyIl4zL58u4E/view?usp=sharing

## License

MIT