# Resume Maker

A MERN stack application that allows users to create and download resumes in PDF format. Users can log in, choose a resume theme, fill in their details, and download their customized resume.

## Features

- **User Authentication**: Secure login and signup functionality using JSON Web Tokens (JWT).
- **Theme Selection**: Choose from default resume themes to personalize your resume.
- **Resume Creation**: Fill in your personal, educational, and professional details.
- **PDF Download**: Generate and download the resume in PDF format.

## Tech Stack

- **Frontend**: ReactJS
- **Backend**: NodeJS, ExpressJS
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)

## Project Timeline

- **Development Period**: October 2023 - January 2024

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Harry212002/ResumeMaker.git
   cd ResumeMaker
2. **Install dependencies for the backend:**:
     cd makemyresumebackend
     npm install
3. **Install dependencies for the frontend**:
    cd makemyresumefrontend
    npm install
4.  **Environment Variables:**
    Create a .env file in the backend directory and add the following
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret

5. **Start the development server:**
   Backend:
   cd makemyresumebackend
   npm run dev
   
   Frontend:
   cd makemyresumefrontend
   npm start

## API Endpoints

- **POST /api/auth/signup**: Register a new user.
- **POST /api/auth/login**: Authenticate and log in a user.
- **GET /api/user/**: Retrieve user details.
- **POST /api/resume**: Create or update resume details.
- **GET /api/resume/download**: Download the resume in PDF format.

## Usage

1. **Login/Register**: Sign up or log in to the application.
2. **Choose Theme**: Select a resume theme from the available options.
3. **Fill Details**: Enter your personal, educational, and professional information.
4. **Download Resume**: Once all details are filled, download the resume in PDF format.






