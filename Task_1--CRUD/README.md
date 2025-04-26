
# 🧩 Node.js CRUD API with MongoDB

A simple and efficient CRUD (Create, Read, Update, Delete) API built using **Node.js**, **Express.js**, and **MongoDB** (via **Mongoose**).

---

## 📦 Features

- ✅ Create a new user
- 📄 Get all users
- 🔍 Get user by ID
- ✏️ Update a user
- ❌ Delete a user

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB** (with **Mongoose**)
- **dotenv** – for environment variable management
- **nodemon** – for hot-reloading during development

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/node-crud-api.git
cd node-crud-api
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Server

```bash
npm run dev
```

Server will start at:

```
http://localhost:5000
```

---

## 📮 API Endpoints

| Method | Endpoint          | Description          |
|--------|-------------------|----------------------|
| POST   | `/api/users`      | Create a new user    |
| GET    | `/api/users`      | Get all users        |
| GET    | `/api/users/:id`  | Get user by ID       |
| PUT    | `/api/users/:id`  | Update user by ID    |
| DELETE | `/api/users/:id`  | Delete user by ID    |

---

## 🔗 Tools

- **MongoDB Atlas** – for database
- **Postman** – for testing the API

---

## 📁 Project Structure

```
├── controllers/
│   └── userController.js
├── models/
│   └── userModel.js
├── routes/
│   └── userRoutes.js
├── .env
├── .gitignore
├── package.json
├── server.js
└── README.md
```

---

## ❤️ Contributing

Feel free to fork this repo, improve it, and create pull requests. Contributions are welcome!

---
