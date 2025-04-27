# 🌫️ Air Pollution Based Disease Prediction System

This project is a desktop-based machine learning application that predicts diseases based on city-specific air pollutant data (PM2.5, PM10, NO₂, and SO₂). It uses a trained Random Forest model and provides a user-friendly GUI built with Tkinter.

---

## 🧠 Objective

To build a predictive system that:
- Analyzes pollution levels of Indian cities
- Predicts the most likely disease caused due to air pollution
- Helps raise awareness about pollution-linked health risks

---

## 📊 Datasets Used

1. **Training Dataset (`pollution_data_10000.csv`)**
   - Contains historical pollution data with labeled diseases.
   - **Columns:** `PM2.5`, `PM10`, `NO2`, `SO2`, `Disease`

2. **City Pollution Dataset (`indian_city_pollution_data.csv`)**
   - Real-time or recent pollution levels of various Indian cities.
   - **Columns:** `City`, `PM2.5`, `PM10`, `NO2`, `SO2`

---

## 🧪 How It Works

1. **Model Training**
   - A Random Forest Classifier is trained using `pollution_data_10000.csv`.
   - Features used: PM2.5, PM10, NO2, SO2
   - Target: Disease label

2. **Prediction**
   - User enters a city name.
   - The app fetches pollution data from `indian_city_pollution_data.csv`.
   - The model predicts the most likely disease based on the pollution data.

3. **User Interface**
   - Built using Tkinter.
   - Includes city input field, styled buttons, and prediction output.

---

## 🖼️ GUI Preview

> ✨ A modern, styled Tkinter UI with a black theme and hover-enabled buttons.

![image](https://github.com/user-attachments/assets/a45ac52f-9e99-4019-9ea0-332762d3018b)


---

## ⚙️ Technologies Used

- Python 3.x
- Tkinter (for GUI)
- Pandas (for data handling)
- Scikit-learn (for machine learning)

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/vi1ka2/air-pollution-disease-predictor.git
   cd air-pollution-disease-predictor
2.**Install Required Libraries**
   pip install pandas scikit-learn
3.**Place the Datasets**
  pollution_data_10000.csv
  indian_city_pollution_data.csv
 Ensure both files are in the same directory as the Python script.
4.**Run the App**
  python app.py

---

## 📌 Features
- City-wise disease prediction
- Trained ML model using real-world pollution data
- Interactive desktop GUI
- Error handling for unknown cities
- Custom styles and animations in UI


---



