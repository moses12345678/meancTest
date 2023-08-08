# React Native Authentication App

This is a React Native application that includes login, registration screens, and a simple home page to verify user authentication.

## Features

- User login and registration screens
- Simple home page to confirm authentication
- **Primary color**: #4caf50
- **Background image**: Cubes Pattern

## API Endpoints

### Login

**API**: [https://meanc4.azurewebsites.net/meanc/login/](https://meanc4.azurewebsites.net/meanc/login/)

**Method**: POST

- Send a POST request with user email and password.
- If the token received in the response is correct, the user is successfully authenticated.

### Registration

**API**: [https://meanc4.azurewebsites.net/meanc/users/](https://meanc4.azurewebsites.net/meanc/users/)

**Method**: POST

- Send a POST request with user email and password.
- The API will create a token in the database for the new user.
- After successful registration, users can log in using their credentials.

## Primary Color

The primary color used throughout the app is **#4caf50**.

## Background Image

The background of the app features a textured pattern obtained from Cubes Pattern.

## Unit Tests

The application includes unit tests to ensure its functionality and components are working as expected.

## Getting Started

To get started with the app:

1. Clone this repository:

   ```bash
   git clone https://github.com/moses12345678/meancTest
