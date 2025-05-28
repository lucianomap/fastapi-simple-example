# 🧾 Simple FastAPI Example

This is a simple RESTful API built with [FastAPI](https://fastapi.tiangolo.com/) that allows you to create, retrieve, and list to-do items.  
It supports basic `POST` and `GET` operations and uses `pydantic` for data validation.

---

## 🚀 Features

- ✅ Create new items with `POST`
- 📋 List all items (with optional limit) with `GET` 
- 🔍 Retrieve item by ID  

---

## 📦 Requirements

- Python 3.7+
- FastAPI
- Uvicorn
- Pydantic

Install the dependencies with:

```bash
pip install -r requirements.txt
```
---

## ▶️ Running the API

You can start the server using `uvicorn`:

```bash
uvicorn main:app --reload
```

---

## 🧪 API Documentation

Once the server is running, you can interact with it using one of either options:

Swagger UI: http://localhost:8000/docs

ReDoc: http://localhost:8000/redoc

---

## 📄 License
This project is open source and available under the MIT License.
