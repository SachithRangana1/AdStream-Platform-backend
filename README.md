##AdStream Platform Backend
Welcome to the AdStream Platform Backend! This is the backend service for the AdStream advertising platform, developed using Node.js, Express.js, NestJS, and PostgreSQL.

Table of Contents
Introduction
Technologies
Installation
Configuration
Running the Application
API Documentation
Contributing
License
Introduction
The AdStream Platform Backend serves as the core API service for the AdStream advertising platform. It handles all backend operations, including data management, user authentication, and business logic for ad serving and management.

Technologies
Node.js: JavaScript runtime for server-side development.
Express.js: Minimalist web framework for building RESTful APIs.
NestJS: Framework for building scalable and maintainable server-side applications.
PostgreSQL: Relational database management system for storing and managing data.
Installation
To get started with the AdStream Platform Backend, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/SachithRangana1/AdStream-Platform-backend.git
Navigate to the project directory:

bash
Copy code
cd adstream-backend
Install dependencies:

bash
Copy code
npm install
Configuration
Before running the application, you need to configure your environment settings.

Create a .env file in the root directory of the project.

Add the following environment variables to the .env file:

dotenv
Copy code
PORT=3000
DATABASE_URL=postgres://postgres:psql@localhost:5432/adstream
Adjust the DATABASE_URL and other variables as needed for your setup.

Running the Application
To start the development server, use:

bash
Copy code
npm run start:dev
For production, build and run the application:

Build the application:

bash
Copy code
npm run build
Start the application:

bash
Copy code
npm run start
API Documentation
The AdStream API documentation is available at API Documentation when the application is running. This documentation provides details about the available endpoints, request/response formats, and authentication requirements.

Contributing
Contributions are welcome! To contribute to the AdStream Platform Backend:

Fork the repository.
Create a new branch for your feature or bugfix.
Make your changes and test them.
Submit a pull request with a description of your changes.
Please ensure your code adheres to the project's coding standards and includes relevant tests.

License
This project is licensed under the MIT License. See the LICENSE file for details.
