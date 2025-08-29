📱 Teen Mobile Addiction Prediction — Machine Learning Project
📌 Project Overview

This project predicts the addiction level of teenagers to mobile phones based on usage patterns, lifestyle, and social habits using Machine Learning.
It demonstrates a complete pipeline: data loading, exploratory analysis, preprocessing, model training, evaluation, and an interactive CLI for real-time predictions.
The addiction level is categorized as Low / Moderate / Severe for easy interpretation.

📂 Project Structure
📁 Mobile-Addiction-Prediction
│── 📄 src/
│    └── mobile_addiction_cli.py   # Main Python script with CLI
│── 📁 data/
│    └── teen_phone_addiction_dataset.csv  # Dataset (local)
│── 📁 notebooks/
│    └── exploration.ipynb         # Optional EDA notebook
│── 📄 requirements.txt            # Dependencies
│── 📄 README.md                   # Project documentation

📊 Dataset Details

Features:

Age → Teenager’s age

Daily_Usage_Hours → Average phone usage per day (hours)

Screen_Time_Before_Bed → Phone usage before sleeping (hours)

Time_on_Social_Media → Time spent on social media daily (hours)

Other optional features: Sleep_Hours, Phone_Checks_Per_Day, Exercise_Hours, etc.

Target:

Addiction_Level → Numeric score mapped to categories:

Low Addiction

Moderate Addiction

Severe Addiction

⚙️ Workflow

1️⃣ Load & Inspect Data → check shape, missing values, basic statistics
2️⃣ Exploratory Data Analysis (EDA) → distributions, correlations, scatter plots
3️⃣ Preprocessing → handle categorical & numeric features
4️⃣ Train-Test Split → 80-20 split for training and evaluation
5️⃣ Train Models → Linear Regression, Random Forest, Gradient Boosting
6️⃣ Evaluate Models → MSE & R² score to select the best model
7️⃣ Select Best Model → highest R² chosen
8️⃣ Interactive CLI → enter user data to predict addiction score and category


📦 Requirements

numpy
pandas
matplotlib
seaborn
scikit-learn


📈 Example CLI Output

=== Mobile Addiction Prediction CLI ===
Type 'quit' anytime to exit.

Enter Age (e.g. 20): 18
Enter Daily Phone Use in hours (e.g. 5): 6
Enter Screen Time Before Bed in hours (e.g. 2): 2
Enter Time on Social Media in hours (e.g. 3): 4

Predicted Addiction Score: 72.50
Category: Severe Addiction
