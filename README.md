

# 🔊 Noise Pollution Prediction Using Machine Learning

This project uses machine learning to predict **noise pollution levels (in decibels)** based on environmental and human activity factors such as traffic density, temperature, humidity, industrial activity, wind speed, and time of day.

## 📂 Project Structure

📁 noise-pollution-predictor/ ├── noise_pollution_data.csv # Dataset (CSV format) ├── noise_prediction.py # Main Python script ├── requirements.txt # Python dependencies └── README.md # Project documentation


---

## 🚀 Features

- Predicts **noise levels (dB)** using Linear Regression
- Takes input features:
  - Traffic density (vehicles/hour)
  - Industrial activity index (0–1)
  - Temperature (°C)
  - Humidity (%)
  - Wind speed (km/h)
  - Time of day (0–23 hours)
- Visualizes actual vs predicted noise pollution levels
- Easy to extend with advanced models (e.g., Random Forest, XGBoost)

---

## 📊 Sample Input Data (`noise_pollution_data.csv`)

```csv
traffic_density,industrial_activity,temperature,humidity,wind_speed,time_of_day,noise_level
120,0.7,30,60,10,9,72
200,0.9,33,55,12,14,85
80,0.2,25,70,8,2,60

🧪 How to Run

    Clone the repo

git clone https://github.com/yourusername/noise-pollution-predictor.git
cd noise-pollution-predictor

Install dependencies

pip install -r requirements.txt

Run the script

    python noise_prediction.py

📦 Dependencies

pandas
scikit-learn
matplotlib

Install via:

pip install pandas scikit-learn matplotlib

📈 Future Improvements

    Use real-time traffic and weather APIs

    Add support for geospatial (GIS) data

    Deploy as a web app with Streamlit or Flask

    Switch to deep learning models for better accuracy

👩‍💻 Author

Agbozu Ebingiye Nelvin
Data Scientist | Environmental AI Researcher
LinkedIn • Email 
⚖️ License

This project is licensed under the MIT License - see the LICENSE file for details.


---

Let me know if you want a `requirements.txt` or a version for a Jupyter Notebook project instead.

