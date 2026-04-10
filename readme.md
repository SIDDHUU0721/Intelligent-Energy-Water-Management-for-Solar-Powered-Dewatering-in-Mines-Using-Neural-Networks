An intelligent energy-water management system using LSTM for solar-powered dewatering optimization.
#  Solar AC Power & Drilling Prediction

##  Overview

This project is an interactive web application built using Streamlit that uses an LSTM deep learning model to predict AC power and provide drilling recommendations.

##  Tech Stack

* Python
* TensorFlow / Keras
* Streamlit
* NumPy, Pandas, Scikit-learn

##  How to Run

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Run the app:
   streamlit run app.py

##  Features

* Single input prediction
* Batch CSV prediction
* Visualization
* Drilling recommendations

##  Files

* app.py → Streamlit app
* scaler.pkl → preprocessing
* lstm_model.keras → trained model

##  Output

* AC Power prediction
* Drilling mode suggestion

##  input screen

<img width="1847" height="775" alt="Screenshot 2026-04-10 103405" src="https://github.com/user-attachments/assets/fe9910ce-cf74-4bbd-bb36-1dda7d456184" />

##  output screen

<img width="1852" height="766" alt="Screenshot 2026-04-10 103434" src="https://github.com/user-attachments/assets/214e3e04-90c8-423c-9a50-031763b41ca6" />

##  Workflow

Input → LSTM Model → AC Power Prediction → Drilling Recommendation

##  visualisation

<img width="1887" height="881" alt="Screenshot 2026-04-10 103503" src="https://github.com/user-attachments/assets/975fe3b4-ec26-442d-a142-c33a25d64f5f" />
