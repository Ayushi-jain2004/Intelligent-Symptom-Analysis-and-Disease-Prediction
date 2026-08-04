# Intelligent Symptom Analysis and Disease Prediction

An AI-powered healthcare application that analyzes user-provided symptoms to predict potential diseases using a Machine Learning model. The system also provides comprehensive health recommendations, including disease descriptions, medications, precautions, diet plans, and workout suggestions to promote better health awareness.

## Features
Predicts diseases based on user-entered symptoms using a trained Random Forest classifier.
Supports intelligent symptom matching with fuzzy string matching to handle spelling errors.
Provides detailed disease descriptions.
Recommends medications, precautions, diet plans, and workout suggestions.
User-friendly web interface built with Flask.
Real-time disease prediction with instant recommendations.
## Tech Stack
#### Backend: Python, Flask
#### Machine Learning: scikit-learn, Random Forest Classifier
#### Data Processing: pandas, numpy
#### Frontend: HTML, CSS, Bootstrap 5
#### Model Persistence: pickle
## Machine Learning Workflow
• Data Collection & Preprocessing

• Feature Engineering

• Random Forest Model Training

• Symptom Matching

• Disease Prediction

• Personalized Health Recommendations
## Installation & Setup
#### Prerequisites
• Python 3.7+
• pip package manager

#### Installation Steps
### 1. Clone the repository
```bash
git clone https://github.com/your-username/Intelligent-Symptom-Analysis-and-Disease-Prediction.git
cd Intelligent-Symptom-Analysis-and-Disease-Prediction
```

### 2. Create a virtual environment (Recommended)

**Windows**
```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install the required dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the application
```bash
python app.py
```

### 5. Open in your browser
```
http://127.0.0.1:5000
```

## Applications
• Healthcare awareness

• Educational demonstrations

• Machine Learning portfolio project

• Symptom-based disease prediction

Disclaimer: This project is intended for educational and research purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Users should consult a qualified healthcare professional for medical concerns.
