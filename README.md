# Bengaluru Home Price Prediction

![image](https://github.com/Neem-Sheth/Bengaluru-House-Prices-Prediction/assets/124123479/4989f84b-47ec-4b97-a3a8-86094bf2b2ca)

This project predicts the price of homes in Bengaluru using a machine learning model. It includes a Flask server for handling API requests and a simple HTML frontend for user interaction.

## Project Overview

This project is designed to help users estimate the price of homes in various locations in Bengaluru based on several input features. During the model-building process, the project covers a wide range of data science concepts and techniques, such as:

- Data loading and cleaning
- Outlier detection and removal
- Feature engineering
- Dimensionality reduction
- GridSearchCV for hyperparameter tuning
- K-Fold cross-validation

## Technologies and Tools Used

- **Programming Languages**: Python, JavaScript
- **Frameworks**: Flask
- **Libraries**: 
  - For Data Science: numpy, scikit-learn
  - For Frontend: jQuery
- **Others**: HTML, CSS

## Application Structure

```plaintext
Bengaluru-Home-Price-Prediction/
├── model/
│   ├── bengaluru_house_prices_model.pickle
│   ├── bengaluru_house_prices.ipynb
│   └── columns.json
├── client/
│   ├── app.html
│   ├── app.css
│   ├── app.js
│   └── bunglow.jpg
├── server/
│   ├── artifacts/
│   │   ├── bengaluru_house_prices_model.pickle
│   │   └── columns.json
|   ├── app.py
|   └── util.py
└── bengaluru_house_prices.csv
```

## Key Features

- **Flask API**: Provides endpoints to get location names and predict home prices.
- **Frontend Interface**: HTML page for user inputs and displaying the estimated price.
- **Machine Learning Model**: Predicts home prices based on location, square feet area, number of BHKs, and number of bathrooms.

## How to Use

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/bengaluru-home-price-prediction.git
    cd bengaluru-home-price-prediction
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Flask server**:
    ```bash
    python app.py
    ```

4. **Open the application in your browser**:
    Navigate to `http://127.0.0.1:5000/` to interact with the application.

## API Endpoints

- **Get Location Names**: `/get-location-names` (GET)
- **Predict Home Price**: `/predict-home-price` (POST)

