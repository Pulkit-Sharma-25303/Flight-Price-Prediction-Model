# Flight-Price-Prediction-Model using Machine Learning
This project aims to predict flight prices based on various factors like departure and arrival cities, booking date, departure date, airline, flight duration, and more. Using a Random Forest machine learning algorithm, this project forecasts ticket prices, helping travelers plan and optimize their bookings.
# Features
* Data Preprocessing: Handling categorical and time-series data.
* Machine Learning Model: A Random Forest regression model for price prediction.
* Model Evaluation: Evaluating the model's performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
# Dataset
The dataset used for this project includes the following features:

* Airline: Name of the airline company (e.g., Jet Airways, IndiGo).
* Date of Journey: The date on which the journey occurs.
* Source: The departure city (e.g., Kolkata, Mumbai).
* Destination: The arrival city (e.g., New Delhi, Bangalore).
* Route: The route taken by the flight.
* Dep_Time: Departure time.
* Arrival_Time: Arrival time.
* Duration: Total duration of the flight.
* Total_Stops: The number of stops the flight makes.
* Additional_Info: Any additional information related to the flight (e.g., in-flight meals not included).
# Prerequisites
* Python 3.x
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
# Results
The Random Forest model achieves the following performance metrics:

* Mean Absolute Error (MAE): Varies based on dataset size and model tuning.
* Root Mean Squared Error (RMSE): Depends on training and feature engineering.
