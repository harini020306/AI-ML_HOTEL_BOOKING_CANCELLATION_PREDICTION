# 🏨 Hotel Booking Cancellation Prediction using Machine Learning

## 📌 Project Overview

The **Hotel Booking Cancellation Prediction** project is a machine learning application that predicts whether a hotel booking is likely to be cancelled before the check-in date. By analyzing customer and booking information, the model helps hotels reduce revenue loss, optimize room allocation, and improve customer management.

A **Streamlit web application** is developed to allow users to enter booking details and instantly predict whether the booking will be cancelled.

---

# 🎯 Objective

The main objective of this project is to build a classification model that predicts hotel booking cancellations based on booking details and customer information.

---

# 📂 Dataset

The dataset contains information related to hotel bookings.

### Features

* Hotel
* Lead Time
* Arrival Date Month
* Stays in Weekend Nights
* Stays in Week Nights
* Adults
* Children
* Babies
* Meal
* Country
* Market Segment
* Distribution Channel
* Previous Cancellations
* Booking Changes
* Deposit Type
* Customer Type
* Average Daily Rate (ADR)
* Required Car Parking Spaces
* Total Special Requests

### Target Variable

* **is_canceled**

  * 0 → Booking Not Cancelled
  * 1 → Booking Cancelled

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Streamlit
* Joblib

---

# 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset Information
* Data Cleaning
* Missing Value Handling
* Duplicate Value Removal
* Statistical Summary
* Correlation Analysis
* Heatmap
* Histograms
* Count Plots
* Box Plots
* Feature Distribution

---

# 🤖 Machine Learning Workflow

1. Import Dataset
2. Data Cleaning
3. Handle Missing Values
4. Encode Categorical Variables
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Save Model
10. Deploy using Streamlit

---

# Machine Learning Algorithm

**Algorithm Used**

* Logistic Regression

Other algorithms that can be compared include:

* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* XGBoost

---

# 📈 Evaluation Metrics

The model is evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

---

# 📁 Project Structure

```
Hotel_Booking_Cancellation/
│
├── app.py
├── hotel_booking_model.pkl
├── scaler.pkl
├── hotel_booking_dataset.csv
├── requirements.txt
├── README.md
└── images/
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Hotel-Booking-Cancellation-Prediction.git
```

Move to the project folder

```bash
cd Hotel-Booking-Cancellation-Prediction
```

Install required libraries

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

The application will launch in your web browser.

---

# 💻 User Inputs

The application accepts booking details such as:

* Hotel
* Lead Time
* Arrival Month
* Adults
* Children
* Meal
* Country
* Market Segment
* Distribution Channel
* Deposit Type
* Customer Type
* Previous Cancellations
* Booking Changes
* ADR
* Parking Spaces
* Special Requests

---

# 🎯 Prediction Output

The application predicts whether the booking will be:

* ✅ Not Cancelled
* ❌ Cancelled

---

# Future Enhancements

* Improve model accuracy using ensemble methods
* Add booking cancellation probability
* Deploy on Streamlit Cloud
* Add interactive dashboards
* Integrate with hotel management systems

---

# Learning Outcomes

Through this project, I gained experience in:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Categorical data encoding
* Feature scaling
* Classification algorithms
* Model evaluation
* Streamlit deployment
* Saving and loading machine learning models

---

# Author

**Harini K**

B.E. Electronics and Communication Engineering

Machine Learning Enthusiast
