# Bitcoin Future Price Prediction

## Overview
This project predicts future Bitcoin prices using machine learning models. It uses historical data and features like opening/closing prices and market cap. The model is built using scikit-learn, and a Streamlit app provides a user-friendly interface to interact with the model and make predictions.

## Dataset
The dataset includes daily Bitcoin statistics:
- **Date**: Date of the observation
- **Open**: Opening price of Bitcoin
- **High**: Highest price during the day
- **Low**: Lowest price during the day
- **Close**: Closing price of Bitcoin
- **Volume**: Total trading volume of the day
- **Market Cap**: Market capitalization of Bitcoin

## Features
- Date
- Open
- High
- Low
- Close
- Volume
- Market Cap

## Installation

### 1. Clone the Repository
Clone the repository to your local machine:
   ```bash
   git clone https://github.com/pythonophile/Bitcoin_Future_Price_Prediction.git
   cd Bitcoin_Future_Price_Prediction
  ```
### 2. Install Dependencies
Install the necessary Python packages:
```
pip install -r requirements.txt
```

### Usage
#### 1. Train the Model
- Train the model using the Jupyter notebook provided:
  ```
  jupyter notebook Bitcoin_Future_Price_Prediction.ipynb
  ```

#### 2. Running the Streamlit App
- Run the Streamlit app for predictions and visualizations:
  ```
  streamlit run app.py
  ```
### Results
The app provides real-time predictions and visualizations based on historical Bitcoin data. Users can interact with the app to see how future price predictions change based on different models and settings.
