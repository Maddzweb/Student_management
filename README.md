# Student_management

1. Run Locally:

git clone https://github.com/Maddzweb/Student_management.git
cd student_management
npm install

2. Create .env file:

MONGO_URI= mongodb+srv://madihamajeed_db_user:Madiha09@studentapi.13pasgc.mongodb.net/
PORT=3000

3. Start server:

npm start
API runs at http://localhost:3000

4. Deployed API

https://student-management-1-a8hu.onrender.com


POST /api/students
{
    "name" : "Anaya",
    "age" : 19,
    "course" : "CS",
    "year" : "2025"
}

GET /api/students