# 🛍️ Amazon Product Review ML Project

##
## 👨🏻‍💻 Project Overview

This study concentrates on the **Amazon Product Review** data in order to understand how the customers respond to their product reviews. The whole process consists of various phases: data cleaning, data exploration, modeling, hyperparameter tuning, and result evaluation and interpretation. The main purpose of the research is to classify the reviews and determine what factors influence the customers’ opinions. The results of the study may be very helpful for businesses, showing them what their customers think and what their product/service weaknesses are.
##

## 📌 Objectives
- In order to prepare the analysis of consumers.
- In order to prepare the report.
- In order to provide the quantitative analysis according to TF-IDF.
- In order to find the way of measuring the sentiment.
- In order to measure the effectiveness of the methodology considering precision, recall, F1 and macro-F1.
- In order to find out the components influencing sentiment.
- In order to provide recommendations on improving goods and services.

##
## 📈 Dataset

Source: https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews

##

## 📊 Exploratory Data Analysis (EDA) Insights 
Key insights extracted from the dataset:

- **Booking Information :**
  - The dataset comprises over **40,000** hotel booking containing information about the guests, rooms, stays, prices, and booking status.
  - The majority of bookings involve two adults, while there are fewer bookings with children.

- **Stay Behavior :**
  - People have different duration of stay on weekends and weedays.
  - The lead time differs a lot between different kinds of bookings, suggesting various booking patterns of behavior.

- **Pricing Behavior :**
  - The average price of the rooms varies from one type room and market to another.
  - Most bookings fall into the low to medium price category, while booking at high prices is a rare phenomenon.

- **Booking Status :**
  - Not_Canceled bookings constitute the bulk of hotel reservations; also, a small portion of the bookings gets canceled.
  - The other booking characteristics can be studied to clarify cancellation behavior.

- **Customer Preferences :**
  - Room type number **1** belongs to the most popular room types.
  - People have different preferences regarding meals, room types, and special requests.

- **Correlations :**
  - There are observable correlations between the lead time, average price, stay duration, amount of guests, and special requests.
  - The correlations point out the factors that can affect the cancellation of bookings and the customers' behavior when booking rooms.
 
---
##
## 📋 Project Pipeline
1️⃣ **Data Processing** : This is the phase where we deal with the incorrect data, eliminate the unnecessary feature variables, convert the categorical data to numerical data, and standardize the integer data.

2️⃣ **Feature Engineering** : We will descover the features, which are crucial in cancelling the bookings like the time prior to checking in, the price of one night, the kind of room, the number of adults and children, the total length of stay.

3️⃣ **Model Selection and Training** : The different algorithms will be implemented during the process from Random Forest and Gradient boosting to Logistics Regression and SVM and topping it off with Naive Bayes and KNN techniques.

4️⃣ **Result Evaluation** : We will conduct a comparison of the different algorithms based on their performance using such metrics as accuracy, precision, recall, F1 score, and MAE for the purpose of defining the most successful prediction algorithm.

5️⃣ **Business Recommendations** : The information obtained by the conduct of the algorithms will be applied for detecting the cacellation tendencies and boosting the company to avoid cancellations, distribute rooms, price the rooms properly, etc.

##

## ⚖️ Machine Learning Models Evaluated

| Model                 | Accuraciy (%) | F1 Score (%) | Training Time (s) |
|----------------------|-------------|-------------|----------------|
| **Random Forest**    | **100.0%**   | **100.0%**   | 0.197          |
| **SVM**             | **100.0%**   | **100.0%**   | 0.008          |
| **Gradient Boosting** | **100.0%**   | **100.0%**   | 0.324          |
| **KNN**              | **98.6%**    | **98.6%**    | 0.003          |
| **Naive Bayes**      | **100.0%**   | **100.0%**   | 0.004          |
| **Logistic Regression** | **98.6%** | **98.6%** | 0.372          |

##

## 🗝️ Key Insights 
- The average cost of room bookings stands at **103.42 currency**.
- The average booking omprises of about **1.85 guests**.
- The overall average number of children coming to the hotel is **0.11**.
- Bookings are customer done on average at the time interval of **85.23 days** before arrival at the hotel.
- The average period of stay is **3.52**.
  - ✅ Non-Cancellations: **67.24%**
  - ❌ Cancellations: **32.76%**
- The meal plan chosen by the most clients holds a leading position in the amount of reservation processing amounting to the most significant number with almost **76.7%**.
- The most commonly chosen accommodation type is room type **1** that has about **76.0%** of the total bookings.
- The hotel is probably to get around **0.62** extra requests for one booking in average.
- About **12.5%** of all bookings made by the hotel guests are done to park their cars.

---

##

## 🗣 Business Recommendations  
1️⃣**Minimize the number of cancellations** - Introduce flexible cancellation policies, provide alerts for bookings and offer discounts for booked rooms that can be cancelled.

2️⃣ **Customized marketing campaigns** - Identify your regular guests and the most lucrative bookings and provide them with personalized services and upgrades making them your loyal clients.

3️⃣ **Develop your pricing strategy for the rooms** - Implement variable pricing and individualized offers to attract more clients and increase your revenue.

4️⃣ **Increase your customer involvement** - Use email or SMS notifications for guests that have already warned the hotel about their cancellation prior to making the booking.

5️⃣ **Promote family and group discounts** - Provide attractive deals and discounts on family or group bookings incorporating children and adults.

6️⃣ **Improve your customer experience** - Find out what special needs your guests have and offer the services accordingly bringing the hotel experience to a new level.

##

## 🤖 Technologies Used

- Python 3.13
- Pandas & NumPy
- Plotly & Matplotlib
- Scikit-learn
- Jupyter Notebook

##
## 🚀 Getting Started
1. Clone this repository
```bash
git clone https://github.com/dharak07/Intro-to-AI-and-Machine-Learning.git
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebook
```bash
jupyter notebook jupyter/Project.ipynb
```
##
## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
