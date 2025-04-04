📘 AI-Based Process Scheduler
An intelligent, machine learning-powered process scheduler that predicts and assigns CPU scheduling priorities based on real-time system usage. This project uses system metrics such as CPU usage, memory usage, and the number of active processes to dynamically decide which processes should be prioritized—just like a smart OS scheduler!

🔍 Features
📊 Collects real-time system data using psutil

🤖 Trains machine learning models (RandomForest, XGBoost) to predict process priority

🧠 Supports hyperparameter tuning for better accuracy

📈 Visualizes data trends with matplotlib and seaborn

🔁 Continuously learns with real-time data logging and retraining

🛠️ Technologies Used
Python

Jupyter Notebook

scikit-learn

XGBoost

NumPy, Pandas

Matplotlib, Seaborn

psutil

🚀 How It Works
System usage data is collected over time (CPU, memory, process count).

Data is logged and used to train a machine learning model.

The model predicts a scheduling priority (a float value).

The system can use this prediction to make scheduling decisions.

📁 Files
AI_Process_Scheduler.ipynb: Main notebook with all code and explanations

system_usage_data.csv: Logged training data from real-time system usage
