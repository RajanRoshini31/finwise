# FINWISE – A Financial Advisor Application

FINWISE is an AI-powered personal finance platform that simplifies budgeting, bill tracking, financial calculators (SIP, mutual funds, stock forecasting), and financial literacy through an all-in-one web-based solution. Built to address the growing need for integrated financial tools and improved financial awareness among young adults, FINWISE combines intelligent automation with user-centric design to empower smarter money management.

Features-

🔐 Secure Login & Dashboard – SHA-256 password hashing with session-based user authentication.
📊 Expense Tracking & Budgeting – Log and categorize expenses, set budgets, and visualize spending.
⏰ Bill Reminders – Schedule recurring bills and receive in-app alerts via Moment.js.
🤖 AI Financial Chatbot – Get real-time financial advice using Google Generative AI.
📈 Stock Price Prediction – Forecast stock trends using a hybrid LSTM + ARIMA model.
🧮 Financial Calculators – Built-in EMI, SIP, FD, and compound interest tools.
📰 Live Financial News – Ticker-based stock news updates using NewsAPI.
🏗 Architecture

Frontend: HTML5, CSS3, JavaScript (ES6+), Chart.js, Plotly.js
Backend: Python, Flask, TensorFlow, Keras, NumPy, scikit-learn, PyMongo
Database: MongoDB (NoSQL)
APIs: Google Generative AI, NewsAPI
Security: SHA-256 hashing, session tokens, input validation

System Design:-

Modular architecture with Flask backend and MongoDB for persistent storage
Predictive models (LSTM + ARIMA) for stock forecasting
Chatbot integration with Google's GenAI for personalized responses

🚀 How to Run Locally

Clone the repository:
git clone https://github.com/RajanRoshini31/finwise.git
cd finwise
File Structure : 
app.py 
-backend folder 
    -all .py files 
-templated folder
    -all .html files

Install Python dependencies:
pip install -r requirements.txt
Set up MongoDB and update the connection URI in the Flask config.
Run the Flask app:
python app.py
Open your browser and navigate to http://localhost:5000

📦 Requirements

Python 3.8+
Flask
TensorFlow, Keras, scikit-learn
MongoDB
Internet access for API calls (chatbot and news)


📚 Future Enhancements

☁ Cloud deployment with real-time syncing
🌐 Banking API integration for live tracking
🔔 Smart alerts for bills and spending
🌎 Multi-currency support
📱 Android/iOS mobile app versions
📖 License

This project is developed as part of an academic curriculum and is available for educational and non-commercial use only.
