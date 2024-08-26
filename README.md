# AdStream Platform Backend
Welcome to the AdStream Platform Backend! This backend service powers the AdStream advertising platform, utilizing modern technologies for high performance and scalability.


## 🚀 Introduction
The AdStream Platform Backend provides the core API functionality for managing advertisements, user data, and analytics. Built with Node.js, Express.js, NestJS, and PostgreSQL, it ensures a robust and scalable solution for ad management.

## 🔧 Technologies
##### Node.js: JavaScript runtime for server-side development.
##### Express.js: Minimalist web framework for building RESTful APIs.
##### NestJS: Framework for building scalable and maintainable server-side applications.
##### PostgreSQL: Powerful, open-source relational database system.

## 🌐 Live Demo
Check out the live demo at Demo Link.

## ⚙️ Installation
Follow these steps to set up the AdStream Platform Backend:

Clone the Repository:

bash
Copy code
git clone https://github.com/SachithRangana1/AdStream-Platform-backend.git
Navigate to the Project Directory:

bash
Copy code
cd adstream-backend
Install Dependencies:

bash
Copy code
npm install
### 🛠️ Configuration
Create a .env File in the root directory of the project.

Add the Following Environment Variables to the .env file:

dotenv
Copy code
PORT=3000
DATABASE_URL=postgres://postgres:psql@localhost:5432/adstream
JWT_SECRET=your_jwt_secret
Adjust the DATABASE_URL and other variables as needed for your setup.

## 🚀 Running the Application
Development Mode
Start the development server:

bash
Copy code
npm run start:dev
Production Mode
Build the Application:

bash
Copy code
npm run build
Start the Application:

bash
Copy code
npm run start
## 📚 API Documentation
The API documentation is available at API Documentation when the application is running. This documentation provides details about the available endpoints, request/response formats, and authentication requirements.

Fork the Repository.
Create a New Branch for your feature or bugfix.
Make Changes and Test Them.
Submit a Pull Request with a description of your changes.
Please adhere to the project's coding standards and include relevant tests.

### 📝 Developer Notes
Code Style: Follow the Airbnb JavaScript Style Guide.
Testing: Use Jest for unit and integration tests.
Database Migrations: Run npm run migrate to apply database migrations.

### 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
