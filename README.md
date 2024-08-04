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
2. **Navigate to the backend directory:**
   ```sh
   cd makemyresumebackendl
   npm install

3. **Navigate to the frontend directory:**
   ```sh
   cd makemyresumefrontend
   npm install

   
4. **Environment Variables**

 1. **Create a `.env` file in the `makemyresumebackend` directory.**

 2. **Add the following environment variables to the `.env` file:**
    
     Replace `your_mongodb_connection_string` with your actual MongoDB connection string and `your_jwt_secret` with a secret key for JWT authentication.

5. **Start the development server:**
   Backend:
   ```sh
   cd makemyresumebackend
   npm run dev
   
  Frontend:
   ```sh
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






