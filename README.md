# Backend-Development-CRUD-student-records-API-week-8
 Student Record API is a backend project built with Node.js, Express.js, MongoDB Atlas, and Mongoose for managing student records. It supports CRUD operations, query filtering by gender, error handling, and persistent data storage. The project uses clean architecture with routes, controllers, models, middleware, and cloud database integration.  

 
Student Record API
Project Overview
Student Record API is a backend application built with Node.js, Express.js, MongoDB Atlas, and Mongoose for managing student records efficiently. It supports full CRUD operations (Create, Read, Update, Delete), query filtering by gender, error handling, and persistent cloud database storage.

This project was migrated from a dummy in-memory array to MongoDB Atlas for real-world backend functionality and deployment readiness.

Features
Create new student records
Get all students
Get a single student by ID
Update student details
Delete student records
Filter students by gender using query parameters
MongoDB Atlas cloud database integration
Clean project architecture using MVC structure
Error handling middleware
Environment variable security with dotenv
Tech Stack
Node.js
Express.js
MongoDB Atlas
Mongoose
Postman
Render (for deployment)
API Endpoints
GET all students
GET /students
GET single student
GET /students/:id
POST create student
POST /students
PATCH update student
PATCH /students/:id
DELETE student
DELETE /students/:id
Query filter by gender
GET /students?gender=Male
GET /students?gender=Female
Example Request Body
{
  "name": "David",
  "email": "david@gmail.com",
  "gender": "Male",
  "phoneNumber": "08012345678"
}
Project Structure
config/
models/
controllers/
routes/
middleware/
server.js
.env
package.json
Installation
npm install
npm run dev
Environment Variables
Create a .env file and add:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
Author
'Kayode Akanni, developed as part of backend API migration and deployment assignment using MongoDB and Mongoose.
