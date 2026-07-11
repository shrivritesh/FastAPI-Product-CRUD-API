# 🚀 FastAPI Product CRUD API

A simple RESTful API built with **FastAPI** to practice backend development. This project performs basic CRUD (Create, Read, Update, Delete) operations for products using PostgreSQL as the database.

The goal of this project was to learn how to build APIs, connect them with a database, and organize a backend application using FastAPI and SQLAlchemy.

---

## ✨ Features

- Create a new product
- Get all products
- Get a product by ID
- Update product details
- Delete a product
- Interactive API documentation with Swagger UI

---

## 🛠️ Tech Stack

- Python
- FastAPI
- SQLAlchemy
- PostgreSQL
- Pydantic
- Uvicorn

---

## 📂 Project Structure

```
.
├── database.py
├── database_models.py
├── main.py
├── models.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/shrivritesh/FastAPI-Product-CRUD-API.git
```

Move into the project

```bash
cd FastAPI-Product-CRUD-API
```

Create a virtual environment

```bash
python -m venv env
```

Activate the virtual environment

**Windows**

```bash
env\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file in the project directory

```env
DATABASE_URL=postgresql://postgres:YOUR_PASSWORD@localhost:5432/ritesh
```

Run the application

```bash
uvicorn main:app --reload
```

---

## 📖 API Documentation

Swagger UI

```
http://127.0.0.1:8000/docs
```

ReDoc

```
http://127.0.0.1:8000/redoc
```

---

## 📌 API Endpoints

| Method | Endpoint         | Description       |
| ------ | ---------------- | ----------------- |
| GET    | `/`              | Welcome message   |
| GET    | `/products`      | Get all products  |
| GET    | `/products/{id}` | Get product by ID |
| POST   | `/products`      | Add a new product |
| PUT    | `/products/{id}` | Update a product  |
| DELETE | `/products/{id}` | Delete a product  |

---

## 📚 What I Learned

- Building REST APIs with FastAPI
- Working with SQLAlchemy ORM
- Connecting FastAPI with PostgreSQL
- Using Pydantic for request validation
- Implementing CRUD operations
- Managing database sessions

---

## 🚀 Future Improvements

- JWT Authentication
- Docker Support
- Unit Testing
- Pagination
- Search & Filtering

---

## 👨‍💻 Author

**Ritesh Srivastav**

GitHub: https://github.com/shrivritesh

LinkedIn: https://www.linkedin.com/in/ritesh-srivastav-2520b7244

---

⭐ If you found this project useful, consider giving it a star.
