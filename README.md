# MERN CRUD App

A simple full-stack CRUD (Create, Read, Update, Delete) application built using the **MERN stack** – MongoDB, Express.js, React.js, and Node.js.

This project allows users to add, view, update, and delete items with a fully functional frontend and backend connected via REST API.

---

## 🔧 Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: MongoDB (Local or Atlas)
- **HTTP Client**: Axios

---

## 📁 Project Structure
mern-crud/

├── backend/
│ ├── models/
│ ├── routes/
│ ├── .env
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── App.js
│ │ └── index.js
│ └── package.json
└── README.md


---

## 🚀 Features

- Add new items
- View all items
- Delete items
- Responsive React UI
- RESTful API using Express

---

## 🛠️ Getting Started

### ✅ Clone the repository
git clone https://github.com/your-username/mern-crud-app.git

cd mern-crud-app
✅ Setup Backend
```
cd backend
npm install
Create a .env file in the backend/ folder:

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/merncrud

```
Start MongoDB (if installed locally):
```
mongod
```
Run backend server:
```
node server.js
```

✅ Setup Frontend
```
cd frontend
npm install
npm start
```
