This project is a web application built using the MERN (MongoDB, Express, React, Node.js) stack. It provides functionalities to manage employee <br>information, including adding, updating, deleting, and viewing employees. The system also supports searching and paginating the list of employees.<br>

Features
Add Employee: Add new employees with details like name, email, phone, department, salary, and profile image.<br>
Update Employee: Update existing employee details.<br>
Delete Employee: Remove an employee from the system.<br>
View Employee: View detailed information about an employee.<br>
Search Employees: Search for employees by name.<br>
Pagination: Navigate through pages of employees.<br>
Technologies Used<br>
Frontend: React.js<br>
Backend: Node.js, Express.js<br>
Database: MongoDB<br>
Styling: Bootstrap<br>
State Management: React Hooks<br>
Installation and Setup<br>
Prerequisites<br>
Make sure you have the following installed on your machine:<br>

Node.js<br>
MongoDB<br>
Clone the Repository<br>
bash<br>
Copy code<br>
git clone https://[github.com/sukri/employee-management-system](https://github.com/Kriti-codes/Employee--Management--System).git
cd employee-management-system<br>
Backend Setup<br>
Navigate to the backend directory:<br>

bash<br>
Copy code<br>
cd backend<br>
Install the dependencies:<br>

bash<br>
Copy code<br>
npm install<br>
Create a .env file in the backend directory and add the following environment variables:
<br>
makefile<br>
Copy code<br>
PORT=8080<br>
MONGO_URI=your_mongodb_connection_string<br>
Start the backend server:<br>

bash<br>
Copy code<br>
npm start<br>
The backend server will run on http://localhost:8080.<br>

Frontend Setup<br>
Navigate to the frontend directory:<br>

bash<br>
Copy code<br>
cd frontend<br>
Install the dependencies:<br>

bash<br>
Copy code<br>
npm install<br>
Start the frontend server:<br>

bash<br>
Copy code<br>
npm start<br>
The frontend server will run on http://localhost:3000.<br>

Usage
Adding an Employee: Click on the "Add" button and fill out the form.<br>
Updating an Employee: Click on the edit icon next to an employee's name, modify the details, and save.<br>
Deleting an Employee: Click on the delete icon next to an employee's name.<br>
Searching for Employees: Use the search bar to find employees by name.<br>
Pagination: Use the pagination controls to navigate through the list of employees.<br>
Project Structure<br>
backend/: Contains the backend code, including routes and database models.<br>
frontend/: Contains the React frontend code.<br>
public/: Public assets for the frontend.<br>
src/: Main source code for the frontend.<br>
