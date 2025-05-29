# Shreya's To-Do App 📝

A full-stack CRUD To-Do application built using the **PERN stack** (PostgreSQL, Express, React, Node.js).

## ⚙️ Tech Stack

- **Frontend**: React, Axios, Bootstrap (or other styling)
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **ORM**: node-postgres (`pg`)

---

## 🏗️ Project Structure
-**/client** → React frontend
-**/server** → Express + Node backend
-**database.sql** → PostgreSQL schema(in the server side)

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/shreya19042001/PERN-Stack.git
cd PERN-Stack

2️⃣ . Set Up PostgreSQL Database
Make sure PostgreSQL is installed and running.

Create a new database:
CREATE DATABASE shreya_todo;
(If you provide database.sql):

psql -d shreya_todo -f database.sql

3️⃣ Configure Backend .env
In the /server folder, create a .env file:

PORT=5000
PG_HOST=localhost
PG_PORT=5432
PG_DATABASE=shreya_todo
PG_USER=your_postgres_username
PG_PASSWORD=your_postgres_password

4️⃣ . Install and Run Server

cd server
npm install
npm run dev
Runs on: http://localhost:5000

5️⃣ . Install and Run Client

cd ../client
npm install
npm start
Runs on: http://localhost:3000

📦 Commands
Server

npm install--	Install backend dependencies
npm run dev--	Run backend in dev mode (with nodemon)
npm start--	Run backend in normal mode

Client

npm install--	Install frontend dependencies
npm start-- Start React dev server
npm run build-- Build production-ready frontend

🌟 Features
✅ Add tasks
✅ Edit tasks
✅ Delete tasks
✅ List all tasks
✅ PostgreSQL data persistence
✅ Simple, clean, and responsive UI

🌍 API Endpoints
Method	Endpoint	Description
GET	/todos	Get all todos
POST	/todos	Add a new todo
PUT	/todos/:id	Update todo by ID
DELETE	/todos/:id	Delete todo by ID

👩‍💻 Author
Made with ❤️ by Shreya
GitHub: shreya19042001

If you want, I can also help you write GitHub Actions workflows or deployment scripts! Want me to set that up for you? 🚀

