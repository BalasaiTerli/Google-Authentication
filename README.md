To start project

To run backend

1)cd backend
2)npm install
3)node server.js

To run frontend

1)cd frontend
2)npm install
3)npm start

# Project Name

This project is a web application that integrates Google OAuth for user authentication, allows users to manage a list of friends, and includes secure, token-based authentication for accessing protected routes. It is built with a Node.js and Express backend, MongoDB for database management, and connects to a frontend (assumed to be React) that communicates with the backend.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
  - [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Features
- **User Authentication**: Google OAuth integration for login.
- **JWT-Based Authorization**: JSON Web Token (JWT) for secure session management.
- **Friend Management**: Users can add, update, and view a list of friends.
- **Rate Limiting**: Protects against abuse by limiting requests to certain routes.
- **Environment Variable Support**: Uses `.env` files for managing sensitive data.

## Technologies Used
- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for building RESTful APIs.
- **MongoDB**: NoSQL database for storing user and friend data.
- **JWT**: JSON Web Tokens for session management.
- **Google OAuth2**: For user authentication.
- **dotenv**: For managing environment variables.
- **CORS**: Cross-Origin Resource Sharing to connect frontend with backend.
- **Rate Limiting**: Limits the number of API requests to avoid abuse.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/en/download/)
- [MongoDB](https://www.mongodb.com/try/download/community) (if using locally)
- [Git](https://git-scm.com/downloads)



