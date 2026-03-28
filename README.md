# 💻 Laptop Price Predictor  

A web application built with **Flask, HTML, CSS, and Jupyter Notebook** that predicts the price of a laptop based on its specifications such as RAM, weight, company, type, operating system, CPU, GPU, and features like touchscreen and IPS display.  

---

## 🚀 Features
- Predicts laptop price based on user inputs.  
- Simple and clean **web interface** using HTML & CSS.  
- Machine learning model trained using Jupyter Notebook.  
- Flask backend to handle requests and predictions.  

---

## 🛠️ Tech Stack
- **Python** (Flask, NumPy, Pickle)  
- **Machine Learning** (trained model stored in `model/predictor.pickle`)  
- **Frontend**: HTML, CSS  
- **Jupyter Notebook** for training and preprocessing  

---



## ⚡ How It Works
1. User enters laptop details in the form (RAM, weight, company, CPU, etc.).  
2. Flask receives the input and processes it into feature vectors.  
3. The trained ML model (`predictor.pickle`) predicts the price.  
4. The result is displayed on the webpage.  

---

## ▶️ Getting Started

### 1️⃣ Clone the Repository

git clone [https://github.com/rasadikak/Laptop_Price_Predictor_new.git](https://github.com/rasadikak/Laptop_Price_Predictor_new.git)



---

2️⃣ Install Dependencies

Make sure you have Python 3.8+ installed. Then install the required packages
pip install -r requirements.txt

---
3️⃣ Run the Application

cd website
python app.py

---

4️⃣ Open in Browser

Go to:
👉 [http://127.0.0.1:5001/](http://127.0.0.1:5001/)

---


📌 Live demo:

[https://rasadikak.pythonanywhere.com/](https://rasadikak.pythonanywhere.com/)

---
## ⚠️ Disclaimer
This project was developed as a **learning and practice exercise**.  
The model is **not trained on a real-world dataset**, and therefore the predicted prices do not reflect actual laptop market values.  
It should not be considered a production-ready or commercially reliable solution.


