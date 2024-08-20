# Jobby App

## Introduction

The **Jobby App** is a React-based web application designed to streamline the job search process. It provides a user-friendly platform for job seekers to find relevant opportunities. The app features a dynamic job search interface, user authentication, and various filters to refine job searches.

## Features

- **Login Authentication**: Secure login with user credentials. Redirects users to appropriate routes based on authentication status.
- **Home Route**: Accessible for authenticated users with a button to navigate to the Jobs Route.
- **Jobs Route**:
  - Fetches and displays job listings from an API.
  - Supports searching and filtering by employment type and salary range.
  - Displays loading indicators and handles errors gracefully.
  - Allows navigation to job details.
- **Job Item Details Route**:
  - Displays detailed information about a specific job.
  - Includes company details, job description, and similar jobs.
  - Provides an option to visit the company website.
- **Not Found Route**: Handles unknown routes and displays a not found page.
- **Header Navigation**: Provides links to navigate between Home, Jobs, and Logout options.

## Installation

1. Clone the repository from GitHub.
2. Navigate to the project directory.
3. Install the necessary dependencies.

## Usage

1. Start the development server.
2. Open your browser and navigate to `http://localhost:3000` to view the application.
3. Use the login page to authenticate. Upon successful login, you will be redirected to the Home Route where you can explore job opportunities and details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **React**: Used for building the user interface and handling the application state.
- **Axios**: Utilized for making HTTP requests to the APIs.
- **CSS**: Applied for styling the components and ensuring a responsive design.
- **Design Assets**: Various image and video resources provided for the UI and UX design.
