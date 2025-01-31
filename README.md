# Job Prediction Using TFT Model

## Overview
This project involves designing and implementing a machine learning model using Temporal Fusion Transformer (TFT) to predict job vacancies across Canada. The model leverages historical data from 2015 to 2023, focusing on labor market trends and vacancy forecasting. The project includes data exploration, cleaning, feature engineering, and model evaluation, with results visualized in an interactive Tableau dashboard.

## Key Features
- **Predictive Model**: Uses TFT to forecast job vacancies in Canada with 90% accuracy.
- **Data Cleaning**: Removes redundant data and stores the clean data in AWS RDS PostgreSQL for efficient storage and retrieval.
- **Feature Engineering**: Optimizes the input features to improve model predictions.
- **Interactive Dashboard**: Visualizes labor trends and forecasts using Tableau, offering actionable insights.

## Technologies Used
- **Python** (Data Exploration & Model Implementation)
- **Jupyter** (Development & Analysis)
- **AWS RDS** (Data Storage)
- **PostgreSQL** (Database)
- **Temporal Fusion Transformer (TFT)** (Machine Learning Model)
- **Tableau** (Data Visualization)

## Steps
1. **Data Exploration**: Read and analyze job vacancy data from 2015-2023.
2. **Data Cleaning**: Preprocess the dataset by removing redundant values and storing it in PostgreSQL.
3. **Model Development**: Implement the Temporal Fusion Transformer model to predict job vacancies.
4. **Model Evaluation**: Achieved 90% accuracy in predicting labor trends and job vacancies.
5. **Dashboard Creation**: Developed a Tableau dashboard for visual insights into the data.

## Setup & Installation

### Prerequisites
- Python 3.x
- Jupyter Notebook
- AWS account for RDS PostgreSQL setup
- Tableau (for visualization)

### Installation
Clone the repository:
```bash
git clone https://github.com/Sanjay-10/Job_Prediction_Using_TFT.git
```
Install required libraries:
```bash
pip install -r requirements.txt
```
Set up AWS RDS and configure PostgreSQL for data storage.

Follow the instructions in the Jupyter notebook for data exploration, cleaning, and model training.

## Running the Model
1. Load the dataset and perform exploratory analysis.
2. Preprocess the data and store it in AWS RDS PostgreSQL.
3. Train the TFT model on the preprocessed data.
4. Visualize the results using Tableau.
