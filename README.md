# Multiple Disease Prediction System

## Overview
The Multiple Disease Prediction System is a machine learning–based web application developed using **Streamlit**.  
It predicts the risk of **Heart Disease** and **Diabetes** based on medical inputs provided by the user.

The application stores user prediction history in a **SQLite database** and generates an alert if diabetes is predicted more than three times, advising the user to consult a nearby healthcare facility.

---

## Features
- Heart Disease Prediction using **Logistic Regression**  
- Diabetes Prediction using a **custom Decision Tree**  
- SQLite database for storing prediction history  
- Alert system for repeated diabetes prediction  
- Interactive and user-friendly Streamlit interface  

---

## Technology Stack
- **Language:** Python  
- **Frontend:** Streamlit  
- **Machine Learning:** Custom Decision Tree & Logistic Regression  
- **Database:** SQLite  
- **Libraries:** NumPy, Pandas  

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/asmriti/Multiple-Disease-Prediction.git
cd Multiple-Disease-Prediction

```

### 2.  Create and Activate Virtual Environment
```bash
python -m venv disease-prediction-env
source disease-prediction-env/bin/activate   # Linux / macOS
# For Windows:
 disease-prediction-env\Scripts\activate
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### 5. Run the Streamlit App
 ```bash  
streamlit run app.py
