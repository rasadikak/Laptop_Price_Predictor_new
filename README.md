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

git clone [https://github.com/rasadikak/laptop-price-predictor.git](https://github.com/rasadikak/laptop_price_predictor.git)

cd website

---

2️⃣ Install Dependencies

Make sure you have Python 3.8+ installed. Then install the required packages
pip install flask numpy

---
3️⃣ Run the Application

python app.py

---

4️⃣ Open in Browser

Go to:
👉 [http://127.0.0.1:5001/](http://127.0.0.1:5001/)

---

📸 Screenshots

![CAPTURE](https://github.com/user-attachments/assets/394e1f43-cd6b-4147-9ac4-d38e6d674cb7)



<img width="614" height="921" alt="Screenshot (261)" src="https://github.com/user-attachments/assets/e1c24fe5-aa5d-4f3c-93bf-16398fc533ff" />




---

📌 Future Improvements

Deploy app on Heroku / Render / AWS.

---
## ⚠️ Disclaimer
This project was developed as a **learning and practice exercise**.  
The model is **not trained on a real-world dataset**, and therefore the predicted prices do not reflect actual laptop market values.  
It should not be considered a production-ready or commercially reliable solution.


