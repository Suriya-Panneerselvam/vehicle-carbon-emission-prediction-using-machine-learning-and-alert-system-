# vehicle-carbon-emission-prediction-using-machine-learning-and-alert-system-

CO₂ Emission Predictor:

This project provides a Python-based tool to predict a vehicle's CO₂ emissions and associated environmental ratings. It leverages a machine learning model to estimate emissions based on key vehicle attributes.

🧐 Overview:

The core of this project is a machine learning model trained on the Fuel Consumption Ratings 2023 dataset. The model uses vehicle specifications like Make, Model, Vehicle Class, Engine Size, Cylinders, Transmission, Fuel Type, and Fuel Consumption to predict the CO₂ Emissions (g/km). After predicting the emissions, the program finds the closest match in the dataset to provide an estimated CO₂ Rating and Smog Rating. It also includes an alert for high CO₂ emissions, defined as a value greater than 150 g/km.

🚀 Getting Started

Prerequisites:

Python 3.x

Jupyter Notebook or a similar environment to run the .ipynb file.

Installation

Clone the repository:

Bash

git clone https://github.com/your-username/carbonemission-predictor.git
cd carbonemission-predictor
Install the required libraries:

Bash

pip install pandas numpy scikit-learn
Usage
Place the Fuel Consumption Ratings 2023.pdf file in the same directory as the carbonemission.ipynb notebook.

Open and run the carbonemission.ipynb notebook in your environment.

The notebook will prompt you to enter the specifications for the vehicle you want to analyze.

Enter the required details, and the program will output the predicted CO₂ Emissions (g/km), Estimated CO₂ Rating, and Estimated Smog Rating.

Example
Here's a sample output after providing vehicle data:

Make: Audi
Model: A3 40 TFSI quattro
Vehicle Class: Subcompact
Engine Size (L): 2
Cylinders: 4
Transmission: AM7
Fuel Type: X
Fuel Consumption (L/100Km): 8.7
Hwy (L/100 km): 6.8

CO₂ Emissions (g/km): 199.00
Estimated CO₂ Rating: 5
Estimated Smog Rating: 6
ALERT: High CO₂ Emissions!
📁 Project Structure
carbonemission.ipynb: The main Jupyter Notebook containing the data processing, model training, and prediction logic.

Fuel Consumption Ratings 2023.pdf: The dataset used to train the machine learning model.

README.md: This file.

🛠️ Built With
Pandas - Data manipulation and analysis.

Numpy - Numerical operations.

Scikit-learn - Machine learning model building.

✍️ Authors
Suriya Panneerselvam
