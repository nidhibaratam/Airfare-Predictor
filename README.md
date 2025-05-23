# Decoding the Skies: An Airfare Predictor

**BARATAM NIDHISHRI**


Traveling between cities in India can often feel like a game of chance when it comes to flight prices. As someone who frequently travels between my hometown and Jaipur for college, I’ve experienced this firsthand. This inspired me to leverage my data skills to build a tool that could predict airfares for various routes across India.

Explore the code: [Colab](https://colab.research.google.com/gist/nidhibaratam/9264b2d7cd515eb8067273fce0bd4364/airfare-predictor-final-version.ipynb) | [GitHub](https://github.com/nidhibaratam/DATA-SCIENCE-PROJECT/blob/main/airfare_predictor_final_version.ipynb)

### The “Why”: Seeking Clarity in India’s Flight Pricing

The often unpredictable nature of flight prices across various routes in India sparked this project.
My own experiences booking flights, including my regular trips between my hometown and Jaipur, highlighted the need for a predictive tool.
The goal is to empower travelers across India with insights into potential flight costs.

### Data Insights from Goibibo for Multiple Routes

I utilized historical flight data from Goibibo, covering numerous routes connecting major Indian cities.
Key data points analyzed include: airline, origin/destination cities, departure/arrival times, flight duration, number of stops, and date of travel.
The aim was to identify general price patterns applicable to various popular routes within India.

### Feature Engineering: Preparing Data for Prediction

Raw flight data was transformed into a format suitable for machine learning.
Categorical features (airlines, cities) were handled using techniques like one-hot encoding.
Temporal features (date of journey) were extracted into components like day of the week and month to capture seasonal or day-specific price trends.
Flight durations were standardized for consistent analysis across different routes.

### Predicting Airfares: The Machine Learning Model

A robust machine learning regression model (such as Random Forest or XGBoost) was chosen for its ability to learn complex patterns in the data.
This model was trained on the Goibibo dataset to predict airfares for various city pairs in India.

### Evaluating Performance: Gauging Prediction Accuracy

The model’s accuracy was assessed using relevant evaluation metrics.
The encouraging results suggest the model can learn meaningful price patterns applicable to a range of Indian flight routes.

### Empowering Travelers Across India

This tool can potentially provide estimated flight prices for numerous routes within India.
It could help travelers identify potentially cheaper times to fly between different cities.
Future development could lead to a user-friendly platform accessible to all Indian travelers.

### My Data Science Journey: Building a Versatile Prediction Tool

The project involved significant steps in data handling, feature engineering, and model selection to cater to multiple flight routes.
Future enhancements could include incorporating real-time data and the impact of festivals or events on prices across different Indian cities.
This project is about bringing more transparency and predictability to air travel within India, benefiting anyone looking to book flights between major cities, not just my own travel needs.

Explore the code on [Colab](https://colab.research.google.com/gist/nidhibaratam/9264b2d7cd515eb8067273fce0bd4364/airfare-predictor-final-version.ipynb) and [GitHub](https://github.com/nidhibaratam/DATA-SCIENCE-PROJECT/blob/main/airfare_predictor_final_version.ipynb). I welcome your feedback and ideas on how to make this tool even more valuable for travelers across India!
