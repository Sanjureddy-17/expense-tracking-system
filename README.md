# 💰 Expense Management System  

An **Expense Management System** with a **Streamlit frontend** and a **FastAPI backend** to track, manage, and analyze expenses efficiently.  

---



## 📂 Project Structure  

expense-management-system/
+  frontend/ # Streamlit application (UI)
+  backend/ # FastAPI backend server (API)
+  tests/ # Unit & integration tests
+  requirements.txt # Python dependencies
+  README.md # Project documentation




---

## ⚙️ Setup Instructions  

### 1. Clone the repository  
```bash
git clone https://github.com/yourusername/expense-management-system.git
cd expense-management-system
```

### 2. Create a virtual environment (recommended)
```bash
python -m venv .venv
source .venv/bin/activate   # On macOS/Linux
.venv\Scripts\activate      # On Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the FastAPI server
```bash
uvicorn backend.server:app --reload
```
- API will be available at: http://127.0.0.1:8000
- Interactive API docs: http://127.0.0.1:8000/docs

### 5. Run the Streamlit app
```bash
streamlit run frontend/app.py
```
- Frontend will be available at: http://localhost:8501

### Running Tests
```bash
pytest tests/
```

## Features

- ✅ Add, edit, and delete expenses

- ✅ Categorize expenses

- ✅ View expense history and summaries

- ✅ Interactive frontend with Streamlit

- ✅ RESTful API backend with FastAPI

## Future Improvements

-  Expense visualization with charts/graphs

-  Mobile-friendly responsive design

-  User authentication & login system

-  Cloud deployment (Docker/AWS/Heroku)

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository

2. Create a new branch (feature-xyz)

3. Commit your changes

4. Push to your branch

5. Open a pull request

## License

This project is licensed under the MIT License.
