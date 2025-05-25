# 📦 Inventory ERP

This is a backend project built with **FastAPI** that simulates a lightweight ERP system for managing products and inventory. It is part of a personal initiative to learn best practices in backend development and work in real-world Git/GitHub environments.

---

## 🚀 Current Features

- Create products with name, description, and initial stock
- Store data in a SQLite database
- Auto-generated API documentation with Swagger (OpenAPI)

---

## 🛠️ Technologies Used

- Python 3.10+
- FastAPI
- Uvicorn
- SQLAlchemy
- SQLite
- Pydantic

---

## ⚙️ Installation & Run

1. **Clone the repository**

```bash
git clone https://github.com/your_username/mini-inventory-erp.git
cd mini-inventory-erp

---

## 💻 Running the FastAPI Server

Once the database is initialized, you can start the development server using Uvicorn:

```bash
uvicorn app.main:app --reload

This will start the API at:
http://localhost:8000

To access the interactive API documentation, go to:
http://localhost:8000/docs

There you can test all endpoints easily through Swagger UI.
