# JobSphere

## Introduction
The **Job Portal** is a web application that connects job seekers with potential employers. It allows companies to post job listings, and applicants can apply for jobs through the platform. This project is built using Node.js and Express for the backend.

## Features
- User authentication and authorization.
- Job posting and management by companies.
- Job application submission by users.
- Middleware for authentication and file handling.
- MongoDB database integration.

## Installation
### Prerequisites
- Node.js (>=14.x)
- MongoDB

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Nikhilkps1904/job-portal.git
   ```
2. Navigate to the backend folder:
   ```sh
   cd your_project_name/backend
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Set up environment variables in a `.env` file:
   ```sh
   MONGO_URI=your_mongodb_connection_string
   SECRET_KEY=your_jwt_secret_key
   CLOUD_NAME=YOUR_cloud_name(cloudniary)
   API_key=
   API_secret=
   ```
5. Start the server:
   ```sh
   npm start
   ```

## API Endpoints
### User Routes
- `POST /users/register` - Register a new user
- `POST /users/login` - Login user

### Company Routes
- `POST /companies` - Create a new company
- `GET /companies` - Get all companies

### Job Routes
- `POST /jobs` - Create a new job
- `GET /jobs` - Get all jobs
- `GET /jobs/:id` - Get a specific job

### Application Routes
- `POST /applications` - Apply for a job
- `GET /applications` - Get all applications

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact (https://github.com/Nikhilkps1904).

