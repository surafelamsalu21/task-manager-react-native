# Task Manager App

Welcome to the Task Manager App! This application helps you organize and manage your tasks efficiently, whether it's for personal use or team collaboration.

## Features

1. **User Authentication**: Secure user authentication system allows users to register, login, and logout.

2. **Task Management**: Create, update, delete, and view tasks with ease. Tasks can have titles, descriptions, deadlines, priorities, and status (pending/completed).

3. **Mobile Responsive**: The app is built using React Native, ensuring a smooth and responsive experience on both iOS and Android devices.

4. **RESTful API**: Backend services are provided via a RESTful API built with Node.js and Express, allowing seamless communication between the frontend and backend.

5. **Token-based Authentication**: Secure communication between the client and server using token-based authentication ensures data privacy and integrity.

6. **Environment Variables**: Sensible configuration using environment variables ensures security and flexibility in deployment environments.

## Setup Instructions

1. Clone the repository: `git clone <repo-url>`
2. Install dependencies: `npm install`
3. Set up environment variables: Create a `.env` file and add necessary configurations.
4. Run the backend server: `npm run server`
5. Run the mobile app:
   - For iOS: `npx react-native run-ios`
   - For Android: `npx react-native run-android`

## Folder Structure

- **src**: Contains the source code for the frontend React Native application.
  - **screens**: Screens/components for various app screens.
  - **services**: Services for handling API requests (e.g., AuthService, TaskService).
- **backend**: Contains the backend Node.js server code.
  - **controllers**: Controllers for handling business logic (e.g., AuthController, TaskController).
  - **middleware**: Middleware for request handling (e.g., AuthMiddleware).
  - **models**: Mongoose models for database schema (e.g., User, Task).
  - **routes**: Routes for API endpoints (e.g., authRoutes, taskRoutes).
  - **utils**: Utility functions (e.g., generateToken).

## Final Notes

Thank you for choosing our Task Manager App! We hope it helps you stay organized and productive. If you have any questions or feedback, feel free to reach out to us. Happy task managing!
# Task Manager App

Welcome to the Task Manager App! This application helps you organize and manage your tasks efficiently, whether it's for personal use or team collaboration.

## Features

1. **User Authentication**: Secure user authentication system allows users to register, login, and logout.

2. **Task Management**: Create, update, delete, and view tasks with ease. Tasks can have titles, descriptions, deadlines, priorities, and status (pending/completed).

3. **Mobile Responsive**: The app is built using React Native, ensuring a smooth and responsive experience on both iOS and Android devices.

4. **RESTful API**: Backend services are provided via a RESTful API built with Node.js and Express, allowing seamless communication between the frontend and backend.

5. **Token-based Authentication**: Secure communication between the client and server using token-based authentication ensures data privacy and integrity.

6. **Environment Variables**: Sensible configuration using environment variables ensures security and flexibility in deployment environments.

## Setup Instructions

1. Clone the repository: `git clone <repo-url>`
2. Install dependencies: `npm install`
3. Set up environment variables: Create a `.env` file and add necessary configurations.
4. Run the backend server: `npm run server`
5. Run the mobile app:
   - For iOS: `npx react-native run-ios`
   - For Android: `npx react-native run-android`

## Folder Structure

- **src**: Contains the source code for the frontend React Native application.
  - **screens**: Screens/components for various app screens.
  - **services**: Services for handling API requests (e.g., AuthService, TaskService).
- **backend**: Contains the backend Node.js server code.
  - **controllers**: Controllers for handling business logic (e.g., AuthController, TaskController).
  - **middleware**: Middleware for request handling (e.g., AuthMiddleware).
  - **models**: Mongoose models for database schema (e.g., User, Task).
  - **routes**: Routes for API endpoints (e.g., authRoutes, taskRoutes).
  - **utils**: Utility functions (e.g., generateToken).

## Final Notes

Thank you for choosing our Task Manager App! We hope it helps you stay organized and productive. If you have any questions or feedback, feel free to reach out to us. Happy task managing!
