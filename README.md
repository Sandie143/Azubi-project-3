# React + Vite

# React Portal Application

This project is a **React Portal** with the following features:


# Azubi Frontend Project

## Overview

This project is a React-based frontend application developed for the Azubi platform. The core files in this project are responsible for key functionalities such as user login, navigation, and dashboard interaction. Below are detailed descriptions of the main components you uploaded:

- User Registration
- User Login
- List of Registered Users and last login time

f the main components you uploaded:

### 1. *LoginPage.jsx*
The LoginPage.jsx component handles user authentication and validation. It provides a form for users to input their credentials (username/email and password), performs form validation, and manages state to track input errors or successful logins. It likely interacts with a backend service to authenticate users and provides feedback such as error messages when login fails.

Key Features:
- User input form for email/username and password.
- State management for input validation.
- Error handling (e.g., incorrect credentials).
- Redirection to the dashboard on successful login.

### 2. *DashboardPage.jsx*
The DashboardPage.jsx is the main interface for authenticated users. Once logged in, users are redirected to this dashboard, which aggregates and displays relevant user data. The dashboard is a dynamic component that may include charts, user-specific data, navigation links, and other interactive elements to allow users to manage their profile, settings, or other features of the platform.

Key Features:
- Dynamic display of user-specific data.
- Integration of charts or data visualization.
- User settings and navigational options.
- Responsive and interactive design.

### 3. *LandingPage.jsx*
The LandingPage.jsx serves as the homepage of the application. It’s the first page users see when they access the platform. The page likely provides an overview of the platform’s features, a call-to-action (such as login or sign up), and navigation links to explore the platform further.

Key Features:
- Introduction to the platform.
- Navigation to login, signup, or other sections.
- Static or dynamic content explaining the platform’s purpose.
- A clean, user-friendly interface to engage new users.
## Table of Contents

1. [Demo](#demo)
2. [Features](#features)
3. [Technologies](#technologies)
4. [Installation](#installation)
5. [Running the Application](#running-the-application)
6. [Folder Structure](#folder-structure)
7. [API Endpoints](#api-endpoints)
8. [Contributing](#contributing)
9. [License](#license)

---

## Demo

Provide a link here to the live demo of the portal if available.

## Features

- **User Registration:** Users can register with an email and password.
- **User Login:** Users can log in using registered credentials.
- **List Users:** Display a list of all registered users and last login.

## Technologies

- **React.js** for the frontend.
- **Tailwind CSS** for styling.
- **AWS Lambda** for serverless backend functions.
- **Axios** for API requests.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BensonGathu/azubi-frontend.git
   ```

2. Navigate to the project directory:

   ```bash
   cd azubi-frontend
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

## Folder Structure

```
.
├── public
├── src
│   ├── pages
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── Dashboard.jsx
│   │   ├── LandingPage.jsx
│   ├── styles
│   │   └── tailwind.css  
│   ├── App.jsx
│   ├── main.jsx
├── .env
├── package.json
├── tailwind.config.js 
├── postcss.config.js 
├── README.md
```

## API Endpoints

Your backend is powered by **AWS Lambda Functions**:

- **POST** `/register`: Registers a new user.
- **POST** `/login`: Authenticates a user and returns a token.
- **GET** `/userdata`: Fetches a list of all registered users (requires authentication).

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License.
 

--

## Project Structure

These three main files make up the core pages of the frontend:

- *LoginPage.jsx*: Handles user authentication and form validation.
- *DashboardPage.jsx*: Displays user-specific data and controls after login.
- *LandingPage.jsx*: The entry point for all users, offering navigation and introduction.

## Installation and Setup

### Prerequisites

- Node.js (>= 14.x.x)
- npm (>= 6.x.x)
- React.js (>= 17.x.x)

### Installation

1. Clone the repository:

   bash
   git clone https://github.com/BensonGathu/azubi-frontend.git
   

2. Navigate to the project directory:

   bash
   cd azubi-frontend
   

3. Install dependencies:

   bash
   npm install
   

### Running the Application

1. Start the development server:

   bash
   npm start
   

2. Open your browser and navigate to:

   
   http://localhost:3000
   

### Build for Production

To create an optimized production build, run:

bash
npm run build


## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

## License

This project is licensed under the MIT License.

---