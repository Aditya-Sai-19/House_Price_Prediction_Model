# 🏡 House Price Prediction Model

A web application that predicts house prices based on various features such as location, size, and other property attributes.  
This project uses a **Ridge Regression model** trained on a real-estate dataset.

[**View Live Demo**](https://bmi-online.vercel.app/)

---

![Project Screenshot](https://raw.githubusercontent.com/Aditya-Sai-19/House_Price_Prediction_Model/main/project-screenshot.png)
---

## 🚀 Features
- **Interactive UI:** Enter property details to get instant price predictions.
- **Machine Learning Model:** Trained using Ridge Regression with optimized parameters.
- **Data Handling:** Preprocessing and feature engineering performed on real estate datasets.
- **RESTful API:** Simple endpoints for programmatic predictions.

---

## 🛠 Technology Stack
- **Backend:** Python, Flask
- **Machine Learning:** Scikit-learn, Pandas, NumPy
- **Frontend:** HTML, CSS
- **Model:** Ridge Regression (`RidgeModel1.pkl`)

---

## ⚙️ Setup and Installation
To run this project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Aditya-Sai-19/house-price-prediction.git
cd house-price-prediction
```

### 2️⃣ Create and Activate Virtual Environment
**For Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```
**For macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run
Run the Flask application:
```bash
python main.py
```
The application will be available at **http://127.0.0.1:5000**

---

## 📂 File Structure
```
├── main.py                      # Flask app entry point
├── house_price_prediction.py    # Model logic and prediction script
├── RidgeModel1.pkl              # Trained Ridge Regression model
├── final_dataset.csv            # Preprocessed dataset
├── archive/
│   ├── train.csv
│   └── test.csv
├── templates/
│   └── index.html               # Frontend HTML
├── requirements.txt             # Project dependencies
└── index.html                   # Alternate UI page (if used)
```

---

## 📊 Dataset
The model is trained on real estate price datasets (`archive/train.csv` & `archive/test.csv`) with feature engineering applied on `final_dataset.csv`.

---

## 👨‍💻 Author
**Aditya Sai**  
- **GitHub:** [@Aditya-Sai-19](https://github.com/Aditya-Sai-19)
- **LinkedIn:** [aditya-sai-3317702a6](https://www.linkedin.com/in/aditya-sai-3317702a6/)

---

## ⭐ Contribute
If you like this project, feel free to **star** ⭐ the repo and contribute by creating pull requests.
