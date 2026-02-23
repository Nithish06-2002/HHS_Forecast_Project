# HHS Forecast Project

Machine Learning Forecasting Dashboard for HHS Care Load Prediction using Python and Plotly.

---

## 📌 Project Overview

This project predicts daily HHS care load using time-series modeling and machine learning techniques.  
It compares actual values against ML forecasts and evaluates model performance using residual analysis and error metrics.

The final output is an interactive dashboard deployed using GitHub Pages.

---

## 🚀 Live Dashboard

🔗 Live Site:  
https://nithish06-2002.github.io/HHS_Forecast_Project/

---

## 📊 Key Features

- Actual vs ML Forecast comparison
- Residual error trend visualization
- Model performance evaluation
- Forecast summary statistics (Average, Max, Min)
- Interactive Plotly dashboard
- Production-ready HTML deployment

---

## 🧠 Modeling Approach

- Feature engineering using lag variables (lag1, lag7, lag14)
- Supervised machine learning regression model
- Residual error analysis for validation
- Forecast performance comparison

---

## 📁 Project Structure

HHS_Forecast_Project/

│
├── index.html                      # Interactive dashboard (GitHub Pages entry)
├── Final_Model_Comparison.csv      # Model evaluation metrics
├── ML_Forecast_Output.csv          # Forecast output data
├── HHS_Forecast_Report.pdf         # Detailed project report
├── notebook.ipynb                  # Development notebook
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Plotly
- Scikit-learn
- GitHub Pages

---

## 📈 Model Evaluation

Model performance was evaluated using:

- Residual error trend analysis
- Forecast vs actual trend comparison
- Statistical summary metrics

The model demonstrates stable prediction behavior with interpretable error distribution.

---

## 📝 How to Run Locally

1. Clone the repository

git clone https://github.com/Nithish06-2002/HHS_Forecast_Project.git

2. Install dependencies

pip install -r requirements.txt

3. Run notebook or regenerate dashboard

fig.write_html("index.html")

---

## 📄 Project Report

Detailed methodology, modeling steps, evaluation metrics, and conclusions are documented in:

HHS_Forecast_Report.pdf

---

## 📜 License

This project is licensed under the MIT License.
