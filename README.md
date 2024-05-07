# Herbarium Project

## Overview

The Herbarium project is a comprehensive system designed to manage and catalog botanical specimens. It consists of both frontend and backend components to provide a user-friendly interface for accessing and updating the database.

## Architecture

The project architecture is divided into two main components:

### Frontend

The frontend is responsible for providing a graphical user interface accessible via a web portal. It utilizes HTML, CSS, and JavaScript to create an intuitive user experience for interacting with the Herbarium system.

### Backend

The backend handles the core functionality of the Herbarium system, including API endpoints for data retrieval and manipulation. It is built using Node.js with Express.js to handle server-side logic and routing. The backend communicates with a MySQL database to store and retrieve botanical specimen information.

## Getting Started

To run the Herbarium project locally, follow these steps:

## Getting Started

To run the Herbarium project locally, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies by running `npm install`.
4. In order to work with MySQL, make sure you have MySQL installed on your machine.
5. Install the `mysql2` package by running `npm install mysql2` in the project directory.
6. Modify the `server.js` file to match your MySQL configuration:

   const connection = mysql.createConnection({
   host: "localhost",
   port: "3306",
   user: "root",
   password: "your_mysql_password", //Replace "your_mysql_password" with your actual MySQL native password
   database: "herbarium",
   });

7. Start the backend server by running `npm start` in the `backend` directory.
8. Start the frontend server by running `npm start` in the `frontend` directory.
9. Access the Herbarium web portal in your browser at `http://localhost:8080`.

## Contributors

- [Seb Correa](https://github.com/sebcopixl)

Feel free to customize this README file with additional information specific to your project!
