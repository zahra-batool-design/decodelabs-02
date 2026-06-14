# decodelabs-02
# 🌸 Iris Flower Classification Web App

A simple Machine Learning web application built with **Python** and **Streamlit** that predicts the species of an Iris flower based on its measurements.

## 📌 Project Overview

This project demonstrates how a machine learning classification model can be used to identify Iris flower species using the famous Iris dataset.

Users can enter flower measurements through a web interface and instantly receive the predicted species.

---

## 🚀 Features

- User-friendly Streamlit interface
- Iris flower species prediction
- Uses the Iris dataset
- Stores prediction history in SQLite database
- Fast and lightweight application

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- SQLite

---

## 📂 Project Structure

```
archive/
│
├── app.py               # Main Streamlit application
├── Iris.csv             # Dataset
├── database.sqlite      # SQLite database
└── README.md            # Project documentation
```

---

## 📊 Dataset

The project uses the famous **Iris Dataset**, which contains measurements of three Iris flower species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

Features used:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Iris-Classification.git
```

### 2. Navigate to the project folder

```bash
cd Iris-Classification
```

### 3. Create a virtual environment (Optional)

Windows

```bash
python -m venv .venv
```

Activate

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install streamlit pandas numpy scikit-learn
```

---

## ▶️ Run the Project

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🗄 Database

The application uses SQLite to store prediction records.

Database file:

```
database.sqlite
```

---

## 📈 Machine Learning Model

The model is trained using the Iris dataset and predicts one of the following classes:

- Setosa
- Versicolor
- Virginica

---

## 📷 Output

The application allows users to:

- Enter flower measurements
- Predict the flower species
- Save prediction history

---
## 📷 Screenshots

### 🏠 Home Page
<img width="951" height="502" alt="image" src="https://github.com/user-attachments/assets/4e56e6d0-a78a-440f-bf6b-c4354d52d6c1" />


### 📊 Prediction Result
<img width="623" height="441" alt="image" src="https://github.com/user-attachments/assets/9a4da18d-d27f-40ff-9fc4-3eeb3a5fa59b" />


## 🎯 Learning Objectives

This project demonstrates:

- Data preprocessing
- Machine Learning classification
- Model prediction
- Streamlit web development
- SQLite database integration

---

## 👩‍💻 Author

**Zahra Batool**

---

## 📄 License

This project is for educational purposes.
