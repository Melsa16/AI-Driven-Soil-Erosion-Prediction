# Soil Erosion Prediction System

A machine learning-based web application that predicts soil erosion risk based on various environmental and soil parameters.

## Features

- Interactive web interface built with Streamlit
- Real-time soil erosion prediction
- Visual representation of predictions using gauge charts
- Detailed recommendations based on prediction results
- Input validation and error handling

## Installation

1. Clone the repository:
```bash
git clone "https://github.com/Melsa16/AI-Driven-Soil-Erosion-Prediction.git"
cd AI-Driven-Soil-Erosion-Prediction
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run this code:
```bash
python CPIFINAL.ipynb
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL

3. Enter the required parameters:
   - Climate parameters (temperature, precipitation, elevation)
   - Location parameters (latitude, longitude, slope)
   - Soil composition parameters (sand, silt, clay content)

4. Click "Predict Soil Erosion" to get the results

## Model Details

The application uses a machine learning model trained on soil erosion data. The model takes into account various environmental and soil parameters to predict the risk of soil erosion.

## Project Structure

- `app.py`: Main Streamlit application
- `CPIFINAL.ipynb`: Jupyter notebook containing model training and analysis
- `soil_erosion_model.joblib`: Trained machine learning model
- `soil_erosion_scaler.joblib`: Data scaler for model inputs
- `requirements.txt`: Python package dependencies

## Contributing

Feel free to submit issues and enhancement requests!

## License

[MIT License] 
