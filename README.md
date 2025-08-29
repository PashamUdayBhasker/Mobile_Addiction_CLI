📱 Mobile Addiction Prediction
📝 Project Overview

This project predicts teen mobile phone addiction levels using machine learning.
The dataset includes lifestyle, study habits, social interactions, and mental health factors.
The goal is to classify addiction into Low / Moderate / Severe categories.

⚡ Features

Exploratory Data Analysis (EDA) with charts & visualizations

Data preprocessing (categorical + numeric features)

Training multiple ML models:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Model evaluation (MSE & R²) and selection of the best model

Interactive Command Line Interface (CLI) for real-time predictions

Addiction score categorized into:

Low Addiction

Moderate Addiction

Severe Addiction

📂 Dataset Columns

Important features used for prediction:

Age

Daily_Usage_Hours

Sleep_Hours

Screen_Time_Before_Bed

Time_on_Social_Media

Phone_Checks_Per_Day

Addiction_Level (target variable)

🗂️ GitHub Folder Structure
mobile-addiction-prediction/
│
├── data/
│   └── teen_phone_addiction_dataset.csv      # Dataset file
│
├── notebooks/
│   └── exploration.ipynb                     # Optional notebook for EDA
│
├── src/
│   └── mobile_addiction_cli.py              # Main Python script with CLI
│
├── requirements.txt                          # Python dependencies
├── README.md                                 # This file
└── .gitignore                                # Ignore unnecessary files (like __pycache__)

🛠️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/mobile-addiction-prediction.git
cd mobile-addiction-prediction


Install dependencies:

pip install -r requirements.txt


Place the dataset in the data/ folder.

Run the CLI to predict addiction levels:

python src/mobile_addiction_cli.py

🎯 Example CLI Run
=== Mobile Addiction Prediction CLI ===
Type 'quit' anytime to exit.

Enter Age (e.g. 20): 18
Enter Daily Phone Use in hours (e.g. 5): 6
Enter Screen Time Before Bed in hours (e.g. 2): 2
Enter Time on Social Media in hours (e.g. 3): 4

Predicted Addiction Score: 72.50
Category: Severe Addiction

📊 Results

Models compared: Linear Regression, Random Forest, Gradient Boosting

Best model selected automatically based on R² score

Prediction output: numeric score + category (Low / Moderate / Severe Addiction)

🚀 Future Work

Improve model using more features (e.g., mental health, parental control)

Build a web interface for easier predictions

Test with larger datasets for better accuracy
