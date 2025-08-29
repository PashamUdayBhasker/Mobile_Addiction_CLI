📱 Teen Mobile Addiction Prediction — ML Project 🚀
🔍 Project Overview

Ever wondered how mobile phone habits affect teen addiction?
This project predicts addiction levels of teenagers based on phone usage, social media, and lifestyle patterns using Machine Learning.

Key features:

Predicts numeric Addiction Score

Categorizes users as Low / Moderate / Severe Addiction

Provides an interactive CLI for real-time predictions

🗂 Project Structure
Mobile-Addiction-Prediction/
│
├── data/
│   └── teen_phone_addiction_dataset.csv      # Dataset (CSV)
│
├── notebooks/
│   └── exploration.ipynb                     # Optional EDA & analysis
│
├── src/
│   └── mobile_addiction_cli.py              # Main Python script + CLI
│
├── requirements.txt                          # Python dependencies
└── README.md                                 # Project documentation

🧩 Dataset Features
Feature	Description
Age	Teenager’s age
Daily_Usage_Hours	Average phone usage per day (hours)
Screen_Time_Before_Bed	Phone usage before sleep (hours)
Time_on_Social_Media	Hours spent on social media daily
Sleep_Hours (optional)	Daily sleep duration
Phone_Checks_Per_Day (opt)	Number of phone checks per day
Addiction_Level	Target numeric score (0-100)

Addiction Categories:

Low Addiction: < 40

Moderate Addiction: 40–70

Severe Addiction: > 70

⚙️ Project Workflow

1️⃣ Load & Inspect Data – check dataset shape & missing values
2️⃣ Exploratory Data Analysis (EDA) – distributions, correlations, scatter plots
3️⃣ Preprocessing – encode categorical, scale numeric features
4️⃣ Train-Test Split – 80-20 split for model evaluation
5️⃣ Train Models – Linear Regression, Random Forest, Gradient Boosting
6️⃣ Evaluate Models – compare MSE & R²
7️⃣ Select Best Model – automatically pick the model with highest R²
8️⃣ Interactive CLI – enter user details → predict addiction score + category

🚀 Installation & Run

1. Clone the repo:

git clone https://github.com/your-username/mobile-addiction-prediction.git
cd mobile-addiction-prediction


2. Install dependencies:

pip install -r requirements.txt


3. Run the CLI:

python src/mobile_addiction_cli.py

🖥 Example CLI Interaction
=== Mobile Addiction Prediction CLI ===
Type 'quit' anytime to exit.

Enter Age (e.g. 20): 18
Enter Daily Phone Use in hours (e.g. 5): 6
Enter Screen Time Before Bed in hours (e.g. 2): 2
Enter Time on Social Media in hours (e.g. 3): 4

📊 Predicted Addiction Score: 72.50
🔥 Category: Severe Addiction

🧰 Tech Stack

Python 🐍

Pandas & NumPy 📊

Scikit-learn ⚡

Matplotlib & Seaborn 🎨

💡 Future Improvements

Add more features (e.g., mental health, parental control)

Build a web or mobile interface

Expand dataset for better accuracy and generalization
