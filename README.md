Website Safety Checker
The Website Safety Checker is a Python-based web application that allows users to check whether a given website URL is safe or potentially malicious. It uses machine learning (Random Forest classifier) to analyze features of the URL and predict its safety status. The tool provides an easy-to-use interface built with Flask and a basic front-end design.

Features:-

•	 Machine Learning Prediction using a trained Random Forest model.
•	 URL Analysis to detect suspicious or malicious patterns.
•	 User-Friendly Web Interface for checking website safety in real-time.
•	 Helps users avoid phishing and potentially harmful websites.
Technologies Used:-

•	 Python
•	 Flask (for backend and routing)
•	 Scikit-learn (for machine learning model)
•	 HTML/CSS (for the front-end UI)
•	 Pandas & NumPy (for data manipulation)

Installation
1. Clone the repository
   git clone https://github.com/yourusername/website-safety-checker.git
   cd website-safety-checker
2. Install dependencies
   pip install -r requirements.txt
3. Run the Flask app
   python app.py
4. Open in Browser
   Visit http://127.0.0.1:5000 in your web browser.
   
How It Works:-
•	• The user enters a URL into the input form.

•	• The backend extracts features from the URL.

•	• The trained Random Forest classifier processes the features.

•	• The application returns a prediction: Safe or Malicious.


Project Structure:
website-safety-checker:-

│
├── app.py                  # Main Flask application
├── model.pkl               # Trained machine learning model
├── templates/
│   └── index.html          # Front-end HTML template
├── static/
│   └── style.css           # Optional CSS styling
├── feature_extraction.py   # Feature extraction logic from URLs
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation

Disclaimer
This project is for educational purposes only and may not be fully accurate in detecting all types of malicious websites. Always use additional tools and precautions when browsing the web.
Author
 –github.com/Rutvik-71
