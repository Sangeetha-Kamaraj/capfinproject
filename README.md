# Bulk Mailer App - Backend

This is the backend portion of the Bulk Mailer application, a tool that allows users to send customized emails to groups of people using the MERN stack (MongoDB, Express, React, Node.js) along with the SendGrid API.


## Project Overview

The backend of the Bulk Mailer App is responsible for handling HTTP requests, managing the database (MongoDB), and integrating with the SendGrid API to send emails. 
It provides RESTful endpoints for user authentication, managing mail groups and templates, and sending bulk emails.

## Setup Instructions

To run the backend of the Bulk Mailer App on your local machine, follow these steps:

1. Clone the repository:git clone https://github.com/Sangeetha-Kamaraj/capfinproject.git
2. Navigate to the project backend directory:cd back
3. Install dependencies:npm install
4. Create a `.env` file in the root directory and add the following variables:
BASEURL=/api/v1
DATABASE=<your-mongodb-url>
Secret_Code=<your-jwt-secret>
Mail_Secret=<your-sendgrid-api-key>
5. Start the development server:
npm start


## Features

- User authentication: Sign up and log in to user accounts.
- Mail group management: Create, update, and delete mail groups.
- Mail template management: Create, update, and delete mail templates.
- Sending bulk emails: Select a group and send custom messages or templates to group members.
- View sent emails: View details of emails sent from the application.

## Technologies Used

- **Express**: Backend framework for handling HTTP requests and routes.
- **MongoDB**: Database for storing user data, mail groups, and templates.
- **SendGrid API**: Integration for sending bulk emails to groups of people.
- **Node.js**: Server-side platform for running the backend code.
- **Axios**: HTTP client for making API requests from the frontend.
- **JWT (JSON Web Tokens)**: Authentication mechanism for securing API endpoints.
- **dotenv**: Library for loading environment variables from a `.env` file.
- **bcrypt.js**: Library for hashing user passwords for storage.








