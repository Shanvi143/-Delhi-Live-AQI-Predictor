# -Delhi-Live-AQI-Predictor
Delhi Real-Time AQI Predictor | XGBoost R² 0.73 | Live APIs (AQICN+Open-Meteo) | Gradio HF Spaces 
🚀 Bachao - Delhi Real-Time AQI Predictor  | XGBoost R² 0.73

Live Demo: https://ffd26b91eb839d2d93.gradio.live/

PROBLEM: Delhi AQI 185-291 (Unhealthy). Need hourly ozone forecast for health alerts.

 SOLUTION: XGBoost Regressor beats Random Forest by 20%!
• R²: 0.73 | MAE: 12.17ppb 
• Features: Solar, Wind, Temp, Month, Day
• Dataset: NYC 1973 → Delhi adapted

🌐 LIVE FEATURES:
• Real APIs: AQICN (ITO station O3) + Open-Meteo
• Gradio UI: Load live Delhi data → Predict
• Categories: Good/Moderate/Unhealthy

RUN LOCALLY:
pip install -r requirements.txt
python app.py

RESULTS:
XGBoost: R² 0.73 | RF: 0.61
Temp(35%) > Solar(28%) > Wind(22%)

#ml #airquality #delhi #hackathon #iitmadras
