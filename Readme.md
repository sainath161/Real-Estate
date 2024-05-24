# Real Estate Application

## Overview

This is a full-featured Real Estate Application built with React.js and Tailwind CSS for the frontend, Redux Toolkit for state management, and Node.js/Express for the backend. It includes functionalities such as user authentication, profile management, listing creation, searching, and more. The application is designed to be user-friendly and efficient, leveraging modern web technologies and best practices.

## Installation

### Clone the repository:

git clone https://github.com/sainath161/Real-Estate.git
cd Real-Estate

### Install dependencies:

#### Frontend

cd client
npm install

#### Backend

cd api
npm install

### Set up environment variables:

Create a .env file in the backend directory and add the following variables:

MONGO=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret

### Run the development server:

#### Frontend:

cd client
npm run dev

#### Backend:

cd api
npm start

## Features

### User Authentication:

    Sign up with email and password
    Sign in with email and password
    Google OAuth integration
    JWT-based authentication
    Middleware for error handling

### User Profile:

    View and update profile information
    Image upload functionality
    Delete user account

### Listings:

    Create new listings
    Upload listing images
    View, update, and delete user listings
    Search for listings

### Contact Landlord:

    Contact the landlord from the listing page

## Technologies Used

### Frontend:

    React.js
    Tailwind CSS
    Redux Toolkit
    Redux Persist

### Backend:

    Node.js
    Express.js
    MongoDB with Mongoose
    JWT for authentication

## Deployement

You can also check out the deployed version at [here](https://real-estate-kj91.onrender.com/)
