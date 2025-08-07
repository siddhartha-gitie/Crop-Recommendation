# Crop Recommendation System

Based on environmental factors like soil type, temperature, humidity, pH, and rainfall, this machine learning-based crop recommendation system assists farmers or agricultural enthusiasts in selecting the best crop to grow.

The system is deployed using Flask and has a clear, intuitive web interface. It predicts the best crop using a trained machine learning model.

## Features

- Input key environmental factors
- Predict the most suitable crop
- Clean and simple web UI built with HTML & CSS
- Powered by machine learning (Random Forest, KNN, Decision Tree)
- Flask-based lightweight backend

## Tech Stack

- Python (ML & backend)
- Flask (Web framework)
- HTML/CSS (Frontend)
- scikit-learn, pandas, numpy (ML processing)

## Project Structure

├── Crop_Pred.ipynb # Machine learning code
├── app.py # Flask application
├── crop_model.pkl # Trained machine learning model
├── label_encoder.pkl # Encodes crop labels
├── index.html # Frontend HTML page
├── requirements.txt # Python dependencies
└── README.md # Project documentation


##  How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Crop-Recommendation.git
   cd Crop-Recommendation

2. Create a virtual environment (optional but recommended)
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
  Install dependencies

3. pip install -r requirements.txt
   Run the Flask app

4. python app.py

5. Open in browser
   Navigate to http://localhost:5000 to use the app.


# Do not modify crop_model.pkl and label_encoder.pkl unless you're retraining the model.


### Future Improvements
Add user authentication
Mobile-responsive UI
Integrate weather API for real-time data
Deploy on cloud (Heroku, Render, etc.)



