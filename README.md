# Resume Builder Website

This project is a Resume Builder website that allows users to create and customize their resumes using various templates. It also includes an Applicant Tracking System (ATS) checker to ensure that the resumes are optimized for job applications.

## Features

- User-provided inputs for personal details, educational qualifications, and work experience.
- Customizable resume templates stored in a MySQL database.
- ATS checker to analyze resumes for compatibility and provide scoring.
- Built with React.js for the front-end and Node.js for the back-end.

## Project Structure

```
resume-builder-website
├── backend
│   ├── controllers         # Contains request handling logic
│   ├── models              # Defines data models for user profiles and resumes
│   ├── routes              # Exports route definitions
│   ├── services            # Contains ATS checking logic
│   ├── app.js              # Entry point for the backend application
│   └── config              # Database configuration settings
├── frontend
│   ├── public              # Public assets
│   ├── src                 # Source files for the React application
│   ├── package.json        # Frontend dependencies and scripts
├── package.json            # Backend dependencies and scripts
└── .gitignore              # Files to be ignored by version control
```

## Getting Started

### Prerequisites

- Node.js
- MySQL

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd resume-builder-website
   ```

2. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```
   cd frontend
   npm install
   ```

### Running the Application

1. Start the backend server:
   ```
   cd backend
   node app.js
   ```

2. Start the frontend application:
   ```
   cd frontend
   npm start
   ```

### Usage

- Navigate to the homepage to create a new resume or check ATS compatibility.
- Fill out the resume form with your details and select a template.
- Use the ATS checker to analyze your resume before submission.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## License

This project is licensed under the MIT License.