# User Registration with SQLite and Express.js

This is a simple Node.js application that allows users to register and store their name and address. It uses an SQLite database to store user information and their addresses, with a one-to-many relationship between the users and addresses.

## Features

- A web form for users to submit their name and address.
- Stores users' names in the `User` table and their addresses in the `Address` table.
- Displays all users and their associated addresses in JSON format on a separate page.
- SQLite database used to store the data.
- Uses Express.js for the backend and handling HTTP requests.

## Installation and Setup

### Prerequisites

- [Node.js](https://nodejs.org/en/download/) installed on your machine.

How to Use
Access the Registration Form:

After starting the server, visit the following URL in your browser:

text
Copy code
http://localhost:5000/
You will be redirected to the user registration form.

Submit the Form:

Enter a user name and address, then submit the form. The user and address will be saved in the database.

View Registered Users and Addresses:

After successful registration, you will be redirected to a page showing all users and their associated addresses in JSON format.

You can also manually visit:

text
Copy code
http://localhost:5000/users
This will display all user entries and their associated addresses.

Project Structure
plaintext
Copy code
├── db/
│   └── database.sqlite3  # SQLite database file (created automatically)
├── app.js                # Main server file
├── package.json          # Project dependencies and scripts
├── README.md             # Project documentation
Technologies Used
Node.js: JavaScript runtime environment
Express.js: Web framework for Node.js
SQLite: Relational database
HTML: Simple form for user input


Deployed Link: