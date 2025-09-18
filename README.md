# 🌸 ML IRIS API Project

This project implements a **Machine Learning model** for classifying the famous **Iris dataset** into species (*Setosa, Versicolor, Virginica*).  
It also includes an **API** to serve the model, along with **unit tests** and **integration tests** to ensure correctness and reliability.  

---

## 📂 Project Structure

ML_IRIS_API_PROJECT/
│── .github/ # GitHub workflows (CI/CD, Actions)
│── static/  # Static files (for UI)
│── .dockerignore  # Docker ignore rules
│── Dockerfile  # Docker image setup
│── IRIS.xls  # Raw Iris dataset (Excel format)
│── Iris1.ipynb  # Jupyter notebook for exploration & model training
│── main.py  # Main API script (FastAPI)
│── model.pkl  # Saved trained ML model
│── requirements.txt  # Project dependencies
│── test_integration.py  # Integration tests for API endpoints
│── unit_test.py # Unit tests for functions/modules


---

## ⚡ Features

- **Data Analysis & Training**: Notebook (`Iris1.ipynb`) explores dataset and trains model.  
- **Model Serving**: API (`main.py`) to serve ML predictions.  
- **Model Persistence**: Saved trained model (`model.pkl`) for reuse.  
- **Testing**: Unit tests (`unit_test.py`) and integration tests (`test_integration.py`).  
- **Dockerized**: Containerized for easy deployment.  

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Omotosho-2579/ML_IRIS_API_PROJECT.git
cd ML_IRIS_API_PROJECT


2️⃣ Create virtual environment & install dependencies
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

pip install -r requirements.txt


3️⃣ Run the API
python main.py


The API should now be available at:
👉 http://127.0.0.1:8000 (FastAPI)


🧪 Running Tests

Run unit tests:
pytest unit_test.py


Run integration tests:
pytest test_integration.py


🐳 Docker Setup

Build the Docker image:
docker build -t iris-api .


Run the container:
docker run -p 8000:8000 iris-api


📊 Dataset

The project uses the Iris dataset (IRIS.csv) containing:

🌱 Sepal Length

🌱 Sepal Width

🌺 Petal Length

🌺 Petal Width

🎯 Target: Iris Species (Setosa, Versicolor, Virginica)


Future Improvement

Deploy on cloud platforms (Heroku)


👨‍💻 Author

Developed with ❤️ by Mohammed Abdulrafiu Omotosho
📧 Contact: abdulrafiumohammed2019@gmail.com


