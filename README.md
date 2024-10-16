# Airline Fare Prediction using Machine Learning

## Project Overview

This project aims to predict airline fares using a Random Forest machine learning model. The model demonstrates strong predictive accuracy, achieving an R² score of **0.804**. This predictive capability can assist travelers and businesses in making informed decisions regarding flight pricing.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Preprocessing](#data-preprocessing)
- [Model Development](#model-development)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

To run this project, you need to have Python 3.6 or later installed. You can set up your environment by installing the required packages using pip:

pip install pandas numpy scikit-learn

## Usage

1. Clone the repository:
   git clone https://github.com/SamJoeSilvano/Airline_Ticket_Fare_Prediction.git

2. Navigate to the project directory:
   cd airline-fare-prediction

3. Run the main script:
   python main.py

## Data Preprocessing

The dataset is preprocessed to ensure high quality and accuracy in predictions. Key steps include:

- Data cleaning to remove any missing or inconsistent entries.
- Feature engineering, including feature selection and encoding of categorical variables.
- Splitting the data into training and testing sets.

## Model Development

The model development involves:

- Using the **Random Forest** algorithm for regression.
- Hyperparameter tuning with **RandomizedSearchCV** to optimize model performance.
- Evaluating the model using metrics such as R² score and Mean Absolute Error (MAE).

## Results

The Random Forest model achieved an R² score of **0.804**, indicating a strong predictive capability for airline fare predictions.

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Jupyter Notebook (for exploratory analysis and visualization)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
