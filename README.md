# Stock Market Prediction using Machine Learning

This project is a web application designed to predict stock prices using machine learning algorithms. The application is built with Python, Flask, HTML, CSS, and JavaScript, and leverages TensorFlow for machine learning and time series analysis algorithms. The model achieves up to 95% accuracy in stock price predictions.

## Overview
The goal of this project is to provide accurate stock price predictions using advanced machine learning techniques. The application allows users to input stock data, train models, and view predictions through a user-friendly web interface.

## Features
- **User-friendly Interface**: Interactive and easy-to-use web application.
- **Accurate Predictions**: Achieves up to 95% accuracy in predicting stock prices.
- **Machine Learning**: Utilizes TensorFlow for building and training the predictive model.
- **Time Series Analysis**: Implements advanced time series analysis algorithms.
- **Visualization**: Provides visual representations of stock trends and prediction results.

## Installation
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/stockmarket-prediction.git
   cd stockmarket-prediction
   
2. **Create and activate a virtual environment**:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

4. **Install the required packages**:
pip install -r requirements.txt
Run the Flask application:
python main.py runserver

## Usage
Open your web browser and navigate to http://127.0.0.1:5000/.
Upload your stock data file (CSV format).
Train the predictive model by clicking the "Train Model" button.
View the predicted stock prices and visualizations.

## Model Training
The model is trained using historical stock data. We use a combination of TensorFlow and time series analysis algorithms to create a predictive model. The training process involves:

Data preprocessing and normalization.
Feature engineering to extract relevant features.
Model selection and training.
Evaluation and tuning to achieve high accuracy.

## Results
Our model achieves an accuracy of up to 95% in predicting stock prices. The results are visualized in the web application, providing insights into stock trends and future prices.

## Screenshots




![a12](https://github.com/pareshkharche/StockMarketPrediction/assets/80632983/db988b69-55c7-4ec5-b47c-ab5b9e6a6fa6)

![a13](https://github.com/pareshkharche/StockMarketPrediction/assets/80632983/03c35df3-9e86-4997-a962-89c6504e5897)

![a14](https://github.com/pareshkharche/StockMarketPrediction/assets/80632983/6990d43b-b94f-4724-ba73-1169c6f5e8cd)

![5](https://github.com/pareshkharche/StockMarketPrediction/assets/80632983/0189031f-f323-43c3-9a2f-e810d9a98ae2)


## Technologies Used
Programming Languages: Python, JavaScript
Web Framework: Flask
Machine Learning: TensorFlow, Keras, Scikit-learn
Data Handling and Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn, Altair
Frontend: HTML, CSS, JavaScript
Additional Libraries: Alpha Vantage, Requests, Tweepy 

## Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

