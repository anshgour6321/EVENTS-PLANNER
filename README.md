# Event Planner Application

## Overview
The Event Planner Application is a web-based solution designed to streamline event management. With a backend built using Node.js and a frontend leveraging HTML, CSS, and JavaScript, it offers users a user-friendly interface for organizing events and dynamic data handling.

## Features
- **User-friendly Interface**: Easily manage events with a simple, intuitive interface.
- **Dynamic Data Handling**: Server-side logic powered by a Node.js backend, allowing real-time data updates.
- **Responsive Design**: The application is fully responsive, ensuring accessibility across multiple devices (desktops, tablets, and mobiles).

## Project Structure

EVENT PLANNER/ ├── backend/ │ ├── controllers/ # Contains backend business logic for handling requests │ ├── models/ # Database models to interact with the database │ ├── routes/ # Defines API routes for CRUD operations │ ├── server.js # Main server file to start the application │ ├── package.json # Node.js dependencies and project configurations │ └── .env # Environment variables (e.g., database credentials, API keys) └── frontend/ ├── css/ # Contains stylesheets for the frontend ├── img/ # Images used in the frontend ├── home.html # Home page of the application ├── index.html # Landing page (entry point of the app) ├── script.js # Contains frontend logic and event handling └── styles.css # Global styles for the website


## Installation and Usage

### Backend
1. **Navigate to the backend folder:**
    ```bash
    cd backend
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Configure environment variables:**
    - Create a `.env` file in the backend directory and configure necessary variables (e.g., database URL, API keys).

4. **Start the server:**
    ```bash
    npm start
    ```

The server will be running on the specified port, and you can access it through your browser or API clients.

### Frontend
 **Open `frontend/index.html` in your browser** to access the application interface. The landing page will load, allowing you to interact with the frontend features.
