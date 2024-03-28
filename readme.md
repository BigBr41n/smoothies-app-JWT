# Smoothie Maker Web App

## Overview

This is a web application for creating and managing smoothie recipes. Users can sign up, log in, [and create their own smoothie recipes] (will be added soon).

## Features

- **User Authentication**: Users can sign up for an account and log in securely.
- **Smoothie Exploration**: Users can browse through a collection of smoothie recipes.
- **Responsive Design**: The application is designed to be responsive and accessible across various devices.

## File Structure

.
├── .env                          # Environment configuration file
├── .gitignore                    # Git ignore file
├── app.js                        # Main application file
├── controllers
│   └── authController.js         # Controller for authentication routes
├── middleware
│   └── authMiddleware.js         # Middleware for authentication
├── models
│   └── User.js                   # User model
├── package-lock.json             # Auto-generated npm package lock file
├── package.json                  # npm package configuration file
├── public
│   ├── smoothie.png              # Smoothie image
│   └── styles.css                # CSS styles file
├── routes
│   └── authRoutes.js             # Authentication routes
├── server.js                     # Server configuration file
└── views
    ├── home.ejs                  # Homepage view
    ├── login.ejs                 # Login page view
    ├── partials
    │   ├── footer.ejs           # Footer partial
    │   └── header.ejs           # Header partial
    ├── signup.ejs                # Signup page view
    └── smoothies.ejs             # Smoothie recipes view



## Setup Instructions

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Set up environment variables by creating a `.env` file with appropriate configurations.
5. Start the server using `node server.js` or `npm start`.
6. Access the application through your web browser.

## Dependencies

- **Express**: Web application framework for Node.js.
- **EJS**: Embedded JavaScript templates for generating HTML markup.
- *(Add any other dependencies your project might have)*

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

