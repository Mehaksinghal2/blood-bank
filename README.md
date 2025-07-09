# Blood-Bank

**Project Description**

The Blood Bank is a full-stack web application designed to streamline the process of managing blood donations and requests. It allows users to register as donors or recipients, manage donation records, and search for available blood types. The application provides complete CRUD (Create, Read, Update, Delete) functionality. Built using the MERN stack, the system ensures real-time updates, responsive design, and secure data handling.

**Technical Decisions and Overview**
**Frontend**
* Framework: React.js for building a responsive, component-based user interface.
* Responsive Design: CSS media queries ensure compatibility across desktop, tablet, and mobile devices.
* User Interface: Intuitive UI that allows users to register, log in, and manage donation or request records.
* State Management: Utilizes React Hooks like useState and useEffect for dynamic state handling.
* Error Handling: Client-side form validations for correct input (e.g., valid blood types, phone numbers).

**Backend**
* Framework: Node.js with Express.js for building RESTful APIs and managing server-side logic.
* Database: MongoDB for storing donor and recipient data, including blood types, availability, and contact info.
* API Endpoints: Exposes RESTful routes for handling donor registration, blood search, and request management.
* Validation: Backend validation using middleware to ensure accurate and complete submissions.
* Error Handling: Structured error responses for client and server issues, ensuring a robust experience.

**Data Management**
* Database: MongoDB is used to store and manage blood donation and request records with flexible schemas.
* CRUD Operations: Allows creating, reading, updating, and deleting donor and request entries.
* Blood Search: Users can search available blood types and donors based on their city or blood group.

**Setup Instructions**
**Prerequisites**
* Node.js
* MongoDB


**Installation**
* Clone the Repository
  ```bash
  git clone https://github.com/Mehaksinghal2/blood-bank.git
  cd blood-bank
  ```
* Install Server Dependencies
  ```bash
  npm install
  ```
* Install Client Dependencies
  ```bash
  cd ../client
  npm install
  ```
* Configure Environment Variables
  * Create a .env file in the backend folder:
    ```bash
    PORT=PORT = 8080
    MONGODB_URI = mongodb://localhost:27017/blood-bank
    JWT_SECRET = your_jwt_secret_key
    ```
* Start MongoDB
Ensure MongoDB is running locally or configure your MONGODB_URI appropriately.
* Run the Backend Server
  ```bash
  cd ..
  npm start
  ```
  * Server runs at http://localhost:8000
