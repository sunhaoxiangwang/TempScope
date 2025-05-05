# TempScope
**TempScope** is a web-based application that uses LSTM neural networks to predict future daily temperatures at the U.S. county level. The system forecasts the next **3 months**, **6 months**, and **1 year** based on historical weather data. Users can select a county and the length of predictions they want via an interactive map and receive real-timetemperature forecasts with visualizations. 
## Features

- Forecast daily temperature for:
  - 3 months
  - 6 months
  - 1 year
- Interactive county selection on a U.S. map
- Real-time model inference with LSTM
- Clean visualization of historical trends and predictions
- Easily extendable for additional regions or data sources

## Technical Stack

- **Python** – Data processing and model development
- **TensorFlow / Keras** – LSTM-based sequence prediction
- **Flask** – Web backend to handle requests and serve visual output
- **JavaScript + HTML** – Interactive frontend
- **Matplotlib / Seaborn** – Time series plots and visual insights
-  – Source of historical county-level climate data

## Project Structure
<pre lang="nohighlight"><code>```text TempScope/ ├── app.py # Flask backend logic ├── myProject.py # LSTM model and preprocessing functions ├── templates/ │ ├── index.html # Map interface for county selection │ └── result.html # Visualization page ├── static/ │ └── plots/ # Generated charts ├── data/ # Historical weather data ├── models/ # Trained LSTM models ├── README.md # Documentation ├── requirements.txt # Python dependencies └── sources.txt # Citation and external resources ```</code></pre>
