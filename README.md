# IPL Win Predictor

## Overview

IPL Win Predictor is a Machine Learning web application that predicts the probability of a team winning an IPL match during the second innings. The prediction is based on real-time match conditions such as batting team, bowling team, target score, current score, overs completed, wickets remaining, and match venue.

The application is built using Python, Scikit-Learn, Streamlit, and Pandas.

---

## Features

* Predicts winning probability for both teams.
* Interactive web interface built with Streamlit.
* Uses a trained Machine Learning model.
* Supports multiple IPL teams and venues.
* Real-time prediction based on match situation.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Jupyter Notebook

---

## Dataset

The model was trained using historical IPL match data.

Files used:

* matches.csv
* deliveries.csv

---

## Project Structure

IPL_WIN_PREDICTOR/

├── app.py

├── pipe.pkl

├── requirements.txt

├── IPL_win_predictor.ipynb

├── matches.csv

├── deliveries.csv

└── README.md

---

## Input Parameters

The model takes the following inputs:

* Batting Team
* Bowling Team
* Match City
* Target Score
* Current Score
* Overs Completed
* Wickets Fallen

---

## Model

The prediction model is trained using Scikit-Learn and saved as a serialized pipeline using Pickle.

The pipeline performs:

* Data preprocessing
* Feature transformation
* One-Hot Encoding
* Logistic Regression prediction

---

## How to Run Locally

1. Clone the repository

git clone <repository-url>

2. Install dependencies

pip install -r requirements.txt

3. Run the application

streamlit run app.py

4. Open the URL displayed in the terminal.

---

## Future Improvements

* Support for all IPL seasons.
* Improved feature engineering.
* Enhanced UI/UX.
* Model comparison using multiple algorithms.
* Deployment on cloud platforms.

---

## Author

Satvik Agrawal

Second-Year Engineering Student
