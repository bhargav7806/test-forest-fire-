# 🌲 Forest Fire Prediction using Machine Learning

This project predicts the **Fire Weather Index (FWI)** — a numerical indicator of fire risk — based on weather and environmental factors such as temperature, humidity, wind speed, and region data.  
The project uses a **machine learning model** trained to help forecast potential forest fire risks.

---

## 🚀 Features
- Predicts **Fire Weather Index (FWI)** using weather inputs.
- User-friendly **Flask web app** interface.
- Data preprocessing and feature scaling for accurate predictions.
- Uses **Ridge Regression** model for better generalization.
- Clean and simple HTML interface for easy interaction.

---

## 🧠 Machine Learning Workflow
1. **Data Preprocessing**
   - Handling missing values  
   - Feature selection and scaling using `StandardScaler`
2. **Model Training**
   - Trained on forest fire dataset  
   - Implemented using `Ridge Regression`
3. **Evaluation**
   - Metrics: MAE, RMSE, and R² Score
4. **Deployment**
   - Flask web app for real-time prediction

---

## 📊 Input Features
| Feature | Description |
|----------|-------------|
| Temperature | Ambient temperature (°C) |
| RH | Relative Humidity (%) |
| Wind | Wind speed (km/h) |
| Rain | Rainfall amount (mm) |
| Region | Encoded region value (North, South, East, West, etc.) |

**Output:**  
🔥 **FWI (Fire Weather Index)** – a value indicating how easily a forest fire could start and spread.

---

## 🧩 Technologies Used
- **Python**
- **Flask**
- **Scikit-learn**
- **Pandas, NumPy**
- **HTML, CSS**

---

## ⚙️ Installation & Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/forest-fire-prediction.git
   cd forest-fire-prediction

