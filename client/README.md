# Sociopedia Frontend

A modern social media application built with React, Redux, and Material-UI.

## Overview

Sociopedia is a full-featured social media platform that allows users to:
- Create and manage profiles
- Share posts with text and images
- Connect with friends
- Like and comment on posts
- Toggle between light and dark modes
- View user profiles and friend lists
- Responsive design for mobile and desktop

## Tech Stack

- **React** - Frontend framework
- **Redux Toolkit** - State management
- **Material-UI** - UI component library
- **React Router** - Navigation and routing
- **Formik** - Form handling
- **Yup** - Form validation
- **React Dropzone** - File upload handling

## Features

### Authentication
- User registration with profile picture upload
- Login with email and password
- JWT token-based authentication

### Social Features
- Create posts with text and images
- Like and unlike posts
- Add and remove friends
- View friend lists
- Comment on posts

### User Interface
- Responsive design for all screen sizes
- Dark/Light mode toggle
- Material Design components
- Clean and modern UI

## Getting Started

1. Clone the repository

2. Install dependencies:

    ```bash
    cd client
    ```
     ```bash
    npm i
    ```

3. Set up environment variables:
Create a `.env` file in the client directory with:

    ```
    REACT_APP_API_URL=http://localhost:3001
    ```

4. Start the development server:
    ```bash
    npm start
    ```

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App

## API Integration

The frontend communicates with a Node.js/Express backend API. Key endpoints include:

- `/auth/login` - User authentication
- `/auth/register` - User registration
- `/users` - User management
- `/posts` - Post management
- `/users/:id/friends` - Friend management

## Component Documentation

### Widgets
- **UserWidget** - Displays user profile information
- **PostWidget** - Renders individual posts
- **FriendListWidget** - Shows user's friends
- **MyPostWidget** - Create new posts
- **AdvertWidget** - Displays advertisements

### Forms
- **LoginForm** - User authentication
- **RegisterForm** - New user registration

### Layout
- **Navbar** - Main navigation
- **FlexBetween** - Flexbox utility component

## State Management

Redux Toolkit is used for state management with the following slices:
- Auth state (user, token)
- Posts
- Theme mode

## Styling

- Material-UI v5 theming
- Responsive design using `useMediaQuery`
- Custom theme with light/dark mode support

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

