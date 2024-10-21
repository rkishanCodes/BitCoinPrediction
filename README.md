Your updated README.md file looks great! Here’s a slightly refined version with consistent formatting and flow:

# Bitcoin Price Prediction using LSTM

This project is a **Bitcoin Price Prediction** web application built with **Streamlit**, utilizing an LSTM model to predict Bitcoin prices. The model is trained using historical data fetched from the Yahoo Finance API. This application showcases both the actual historical prices and predicted future prices of Bitcoin.

## Live Demo

You can view the live demo of this app deployed on Render [here](https://bitcoinprediction.onrender.com/).

## Features

- Displays Bitcoin price data from 2015-01-01 to 2023-11-30.
- Predicts future Bitcoin prices using an LSTM model.
- Interactive charts displaying actual and predicted prices.
- Supports future predictions for the next 5 days.

## Technologies Used

- **Streamlit**: For building the web application.
- **Keras & TensorFlow**: For the LSTM model and predictions.
- **Yahoo Finance API (yfinance)**: For fetching Bitcoin price data.
- **Pandas & NumPy**: For data manipulation and analysis.
- **Scikit-learn**: For scaling the data.

## How to Run the Project Locally

### Step 1: Clone the repository
```bash
git clone https://github.com/rkishanCodes/BitCoinPrediction.git
cd BitCoinPrediction

Step 2: Create a virtual environment

python3 -m venv venv
source venv/bin/activate    # On macOS/Linux
# OR
venv\Scripts\activate       # On Windows

Step 3: Install the required dependencies

pip install -r requirements.txt

Step 4: Run the Streamlit app

streamlit run app.py

Contact

For any inquiries or feedback, feel free to reach out via email: rkishan.codes@gmail.com
