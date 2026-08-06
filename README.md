# 🚖 Cab Fare Prediction using Machine Learning

## 📌 Project Overview
This project demonstrates the basics of **Machine Learning** using a synthetic Uber ride dataset. It predicts the fare of a cab ride based on the travel distance using **Linear Regression** and also groups similar rides using **K-Means Clustering**.

The project is intended as a beginner-friendly introduction to both **Supervised Learning** and **Unsupervised Learning**.

---

## 🎯 Objectives

- Generate a synthetic Uber ride dataset.
- Predict cab fares based on travel distance.
- Visualize the relationship between distance and fare.
- Group similar rides into clusters using K-Means.
- Understand the difference between supervised and unsupervised learning.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

This project uses a **synthetically generated dataset**.

### Features

| Feature | Description |
|---------|-------------|
| distance_KM | Distance travelled in kilometers |
| price_INR | Cab fare in Indian Rupees |

- Number of records: **500**
- Data generated using NumPy

---

## 🔄 Workflow

1. Generate synthetic cab ride data.
2. Create a Pandas DataFrame.
3. Train a **Linear Regression** model.
4. Predict the fare for a new ride.
5. Visualize actual data and regression line.
6. Apply **K-Means Clustering**.
7. Visualize ride clusters.

---

## 🤖 Machine Learning Models

### 1. Supervised Learning
**Algorithm:** Linear Regression

Predicts the cab fare using the ride distance.

### 2. Unsupervised Learning
**Algorithm:** K-Means Clustering

Groups rides into three different clusters based on distance and fare.

---

## 📊 Output

The project produces:

- Predicted fare for a 10 km ride.
- Scatter plot of actual fares.
- Regression line.
- Cluster visualization of rider groups.

---

## 📷 Sample Output

### Fare Prediction
```
The AI predicts a 10 km ride will cost: Rs. 188.29
```

### Visualizations

- Scatter plot with Linear Regression line
- K-Means Clustering visualization

---

## 📁 Project Structure

```
Cab_Fare_Prediction/
│
├── Cab_Fare_Prediction.ipynb
├── README.md
```

---

## 🚀 Future Improvements

- Use a real Uber dataset.
- Add multiple input features such as:
  - Time of day
  - Traffic conditions
  - Surge pricing
  - Weather
- Compare different regression algorithms.
- Build a web application using Flask or Streamlit.

---

## 👩‍💻 Author

**Jaishree K S**

BE Information Science and Engineering

GitHub: https://github.com/Jaishree-jusy
