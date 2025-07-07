🩺 Insurance Charges Predictor:

A Streamlit web application that predicts medical insurance charges based on user input using a Linear Regression model. It also includes a visual representation of the prediction on a scatter plot of BMI vs Charges.

 Live Demo: https://insurance-predict-23.streamlit.app/

 📌 Features:
 Predicts insurance charges using features like age, BMI, sex, smoker status, region, and number of children.
Interactive and user-friendly web interface built with Streamlit.
Real-time data visualization using Plotly.
Displays a sample of the dataset for transparency and insight.

📊 Tech Stack:
Frontend: Streamlit
Backend: scikit-learn (Linear Regression), Pandas, NumPy
Visualization: Plotly

🧠 Model Details:
Model: Linear Regression
Preprocessing:
One-hot encoding for categorical features (sex, smoker, region)
Numerical features passed through directly (age, bmi, children)
Dataset: insurance.csv

Project structure:
insurance-charges-predictor

│

├── insurance.csv               # Dataset file

├── app.py                      # Main Streamlit application

├── requirements.txt            # Python dependencies

└── README.md                   # Project documentation (this file)

Dataset: insurance.csv

▶️ How to Run Locally:
1. Clone the repository
git clone https://github.com/your-username/insurance-charges-predictor.git
cd insurance-charges-predictor

2.Create and activate a virtual environment
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

3.Install dependencies
pip install -r requirements.txt

4.Run the Streamlit app
streamlit run app.py

