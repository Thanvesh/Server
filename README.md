**Task Manager API**
The Task Manager API is a RESTful web service built with Node.js and Express.js. It provides endpoints for managing user accounts and tasks.

**Features**
  User authentication (login, signup, password reset)
  User management (change role)
  Task management (create, read, update, delete)
**Prerequisites**
  Node.js installed on your machine
  SQLite database (configured in task_manager.db)
  Installation
**Clone the repository:**
  bash
  Copy code
  git clone https://github.com/Thanvesh/task-manager-api.git
**Install dependencies:**
  bash
  Copy code
  npm install
**Start the server:**
  bash
  Copy code
  npm start
  Usage
  API base URL: http://localhost:3000
  Refer to the API Documentation for detailed information on endpoints and usage.

**Configuration**
  JWT_SECRET: Set your JWT secret key in the .env file or directly in the code (JWT_SECRET variable).
  Contributing
  Contributions are welcome! Please follow the Contribution Guidelines.


**Acknowledgements**
  Express.js
  SQLite
  bcrypt
  jsonwebtoken
