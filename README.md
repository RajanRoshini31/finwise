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
<pre>## 📁 Project Structure

├── app.py # Main application entry point 
├── backend/ # Backend logic and utilities
│ ├── login.py
│ ├── predict.py
│ └── ... # Additional backend Python files
├── templated/ # HTML templates for the frontend
│ ├── index.html
│ ├── login.html
│ └── ... # Additional HTML template files
</pre>
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

![IMG-20250602-WA0002](https://github.com/user-attachments/assets/c006c623-ebb5-437c-b8a2-5ebd90bc8684)
![IMG-20250602-WA0003](https://github.com/user-attachments/assets/fa321a53-6385-443f-85cf-8ff3f27b4596)

![IMG-202506![IMG-20250602-WA0005](https://github.com/user-attachments/assets/68b42ab1-1f84-4597-a47f-6845b1c267b0)
02-WA0004](https://github.com/user-attachments/assets/ea423a85-2d76-4582-993b-2ff9b956e98d)
![IMG-20250602-WA0006](https://github.com/user-attachments/assets/35b3d911-b2cf-4fbf-b257-ce19d56fa9d4)
![IMG-20250602-WA0007](https://github.com/user-attachments/assets/b9588377-bac7-40ce-b0ea-21cb87f2811d)
![IMG-20![WhatsApp Image 2025-06-02 at 21 51 26_736d77d0](https://github.com/user-attachments/assets/7368a967-4172-4490-a6c8-6637670d5767)
250602-WA0008](https://github.com/user-attachments/assets/9db5ea83-b3d0-4abc-a540-f34654bc1ebe)



![WhatsApp Image 2025![WhatsApp Image 2025-06-02 at 21 57 34_86f75e7a](https://github.com/user-attachments/assets/973e2d38-98d8-47cc-823c-82bd5ddd5dd5)
-06-02 at 21 52 57_7668c617](https://github.com/user-attachments/assets/4b1e8850-3153-4d11-98e2-3b2a643e95f5)

This project is developed as part of an academic curriculum and is available for educational and non-commercial use only.
