
# 🐦✈️ Bird Strike Severity Prediction Using Machine Learning


> A machine learning solution to predict and reduce the severity of bird strikes in aviation.
> Built with ❤️ for flight safety and data-driven decision making.

---

## 📊 Overview

Bird strikes are a serious safety concern in aviation. This project uses historical data and a **Random Forest Classifier** to:

✅ Predict the **severity** of bird strikes  
✅ Identify high-risk **altitudes** and **flight phases**  
✅ Improve **safety protocols** and **resource allocation**  
✅ Support **proactive planning** for airports and airlines

---

🔍 Problem Statement

- Bird strikes are rising due to growing wildlife near airports.
- Severe strikes can damage engines, delay flights, or cost millions.
- Predicting strike **severity** enables early intervention and safety improvements.

---

🧠 ML Approach

**Model Used:** `RandomForestClassifier`  
**Accuracy Achieved:** ✅ 92%

🎯 Key Features:
- `Altitude bin`
- `Phase of flight`
- `Sky conditions`
- `Wildlife size`
- `Cost: Total $`

**Target Variable:** `Effect: Indicated Damage`  
➡️ Categorical prediction: No Damage, Minor, Substantial, Destroyed

🛠️ How It Works

```python
# Load & preprocess data
df.fillna(...)  

# Feature engineering
X = pd.get_dummies(df[features])
y = df[target]

# Model training
model = RandomForestClassifier()
model.fit(X_train, y_train)

# Evaluation
accuracy_score(y_test, model.predict(X_test))
````

---

📈 Visual Insights

* 📌 Heatmaps: Strike frequency by altitude & phase of flight
* 📊 Bar Charts: Airlines most affected
* 📉 Trend Graphs: Annual cost and strike counts

> **Insight**: Majority of strikes occur below 1000 ft during takeoff & landing.

---

🧪 Results & Benefits

| Feature            | Impact                          |
| ------------------ | ------------------------------- |
| Model Accuracy     | ✅ 92%                           |
| Risk Detection     | 🎯 High during low-altitude     |
| Safety Improvement | ✈️ Adjust procedures, protocols |
| Cost Efficiency    | 💰 Target bird control efforts  |


 🙏 Acknowledgements
* Developed By: [Rudra Pratap Singh](www.linkedin.com/in/rudrasinghpratap)


