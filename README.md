# lab-crud-api
This project is a simple CRUD API built with Node.js, Express, and MySQL.
It demonstrates how to manage students and courses data, connect to a database, and test endpoints with Postman.

---

Project Overview:

Backend Framework: Express.js
Database: MySQL (via phpMyAdmin / XAMPP)
ORM/Driver: mysql2
Dev Tools: Nodemon, dotenv, Postman

Features implemented:
CRUD for students
CRUD for courses
CORS enabled for cross-origin requests
Environment variables managed via .env

---

 Setup Steps
1. Clone the repository:```bash
git clone https://github.com/<your-username>/lab-crud-api.git
cd lab-crud-api

2. Install Dependencies:
   npm install
3. Configure environment variables:
    •    Copy .env.example to .env
    •    Update with your MySQL username, password, and database name:
----> DB_HOST=localhost
DB_USER=root
DB_PASS=yourpassword
DB_NAME=lab_crud
DB_PORT=3306
PORT=3000

4. Start the Server
   npm run dev

5. Confirm the health check
   Open (http://localhost:3000/api/health) in your browser or Postman


---

Endpoints :)

Students
    •    GET /students → Get all students
    •    GET /students/:id → Get student by ID
    •    POST /students → Create new student
    •    PUT /students/:id → Update student by ID
    •    DELETE /students/:id → Delete student by ID

Courses
    •    GET /courses → Get all courses
    •    GET /courses/:id → Get course by ID
    •    POST /courses → Create new course
    •    PUT /courses/:id → Update course by ID
    •    DELETE /courses/:id → Delete course by ID

⸻

 How to Run
    •    Start MySQL in XAMPP (default port 3306)
    •    Run the Node.js server with npm run dev
    •    Test the API endpoints using Postman
   
