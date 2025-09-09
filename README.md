# SCT_DS_3
📊 Term Deposit Subscription Prediction This project is a Flask-based Machine Learning Web Application that predicts whether a client will subscribe to a term deposit based on demographic, financial, and campaign-related details. It uses a trained scikit-learn model (model.pkl) and provides a simple web interface for users to enter client information and get predictions instantly.

🚀 Features 🧠 ML Model trained to predict subscription likelihood. 🌐 Flask Web App for easy interaction. 📊 User Input Form with demographic & financial details. ✅ Instant prediction with clear output (Yes/No).

🛠️ Tech Stack Python Flask NumPy Scikit-learn

📂 Project Structure ├── app.py # Main Flask application
├── model.pkl # Trained ML model
├── requirements.txt # Dependencies
├── templates/
│ ├── index.html # Input form page
│ ├── result.html # Prediction result page

⚙️ Installation & Setup 0)Clone the repository 1)Create a virtual environment (optional but recommended) 2)python -m venv venv source venv/bin/activate # On Linux/Mac venv\Scripts\activate # On Windows 3)Install dependencies 4)pip install -r requirements.txt 5)Run the Flask app 6)python app.py 7)Open in browser http://127.0.0.1:5000/

🎯 Usage Enter client details (age, job type, marital status, etc.) in the web form. Click Predict.
The app will display: ✅ Client will subscribe (Yes) ❌ Client will not subscribe (No)

📦 Requirements See requirements.txt : Flask NumPy Scikit-learn

📸 Screenshots (Optional) Add screenshots of your web app UI here for better presentation.

🤝 Contributing Contributions are welcome! Feel free to open issues and submit pull requests.
