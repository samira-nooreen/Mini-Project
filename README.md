# Mini-Project
Forecast4Six using Ml

# 🏏 Forecast4Six: Cricket Analytics & Prediction Dashboard

**Forecast4Six** is an intelligent cricket analytics platform that combines machine learning, NLP, and weather forecasting to provide real-time match insights. Built using **Python** and **Streamlit**, it allows users to predict match scores, classify live commentary, and assess weather conditions that could impact gameplay.

---

## 🔧 Features

### 1. 🧠 Score Prediction (ML)
- Predict total team scores using **Linear Regression** and **Random Forest**.
- Input features include team stats, overs, runs, and wickets.

### 2. 🗣️ NLP Commentary Classification
- Classifies ball-by-ball commentary into:
  - `FOUR`
  - `SIX`
  - `WICKET`
  - `OTHER`
- Utilizes **TF-IDF** + **Logistic Regression** pipeline.

### 3. 🌦️ Weather Forecasting
- Fetches **real-time weather data** using API (e.g., OpenWeatherMap).
- Displays temperature, humidity, and weather condition.
- Highlights how weather could impact match dynamics.

### 4. 🖥️ Streamlit Dashboard
- Clean and interactive UI
- Easy input forms for predictions
- Real-time classification and weather data display

---

## 📊 Tech Stack

| Component              | Technology Used            |
|------------------------|----------------------------|
| Backend (ML & NLP)     | Python, Scikit-learn       |
| Text Classification    | TF-IDF, Logistic Regression|
| Score Prediction       | Linear Regression, Random Forest |
| Weather API            | OpenWeatherMap (or similar)|
| Dashboard              | Streamlit                  |
| Data Handling          | Pandas, NumPy              |
| UI Enhancements        | Custom CSS in Streamlit    |

---

## 📁 Project Structure

Forecast4Six/
├── data/ # Match and commentary datasets
├── models/ # Saved ML models
├── NLPCommentary.py # Commentary classifier module
├── ScorePredictor.py # Score prediction logic
├── WeatherModule.py # API calls and weather processing
├── app.py # Main Streamlit app
├── README.md
└── requirements.txt


---

## 🚀 Getting Started

### 🔗 Requirements
- Python 3.8+
- `scikit-learn`, `pandas`, `numpy`, `streamlit`, `requests`

### 🔨 Installation

```bash
git clone https://github.com/yourusername/Forecast4Six.git
cd Forecast4Six
pip install -r requirements.txt
streamlit run app.py

📷 Screenshots
Score Prediction	Commentary Classification	Weather Integration

<img width="377" height="710" alt="image" src="https://github.com/user-attachments/assets/5845de59-1213-43b8-ab2f-979695c96e67" />
<img width="460" height="486" alt="image" src="https://github.com/user-attachments/assets/dbf51da4-93da-44b2-84c9-7203b23f1a25" />

📚 Research Reference
Saikia, H., & Bhattacharyya, D. (2019). IPL Match Outcome Prediction using Machine Learning.
Real-world examples show weather data significantly influences match strategy and performance.

💡 Future Enhancements
Add match winner prediction

Integrate live match feeds

Use deep learning (e.g., LSTM) for richer NLP analysis

Player-based predictions and performance tracking

👩‍💻 Author
Samira
ML & Cricket Enthusiast 🧠🏏
GitHub • LinkedIn

📜 License
This project is licensed under the MIT License.
Feel free to use and contribute!



