# AI Medical Assistant Bot

## Overview

AI Medical Assistant Bot is a Flask-based web application that helps users understand their symptoms and medical reports using Google's Gemini AI. The system provides educational medical information, summarizes uploaded medical reports, detects emergency symptoms, and encourages users to seek professional healthcare advice when necessary.

## Features

### Symptom Analysis

* Users can enter symptoms in natural language.
* AI provides possible causes and general recommendations.
* Responses are generated using Google Gemini AI.

### Medical Report Summarization

* Upload PDF medical reports.
* Extracts text from the report.
* Generates a simple patient-friendly summary.

### Emergency Detection

* Detects critical symptoms such as:

  * Chest pain
  * Difficulty breathing
  * Stroke symptoms
  * Severe bleeding
  * Heart attack indicators
* Displays an emergency warning message.

### Safety Measures

* Educational purposes only.
* Does not provide a final medical diagnosis.
* Encourages consultation with healthcare professionals.

## Technologies Used

* Python
* Flask
* HTML
* CSS
* Google Gemini API
* PyPDF2

## Project Structure

AI-Medical-Assistant/

├── app.py

├── requirements.txt

├── Procfile

├── .gitignore

├── templates/

│   └── index.html

├── static/

│   └── style.css

└── uploads/

## Installation

### Clone Repository

git clone https://github.com/yourusername/ai-medical-assistant.git

cd ai-medical-assistant

### Create Virtual Environment

python -m venv venv

### Activate Virtual Environment

Windows:

venv\Scripts\activate

### Install Dependencies

pip install -r requirements.txt

### Configure Environment Variables

Create a .env file:

GEMINI_API_KEY=your_gemini_api_key

### Run Application

python app.py

Open:

http://127.0.0.1:5000

## Usage

### Symptom Analysis

Enter symptoms such as:

* Fever and headache
* Cough and sore throat
* Stomach pain and nausea

The AI assistant will provide educational information and recommendations.

### Medical Report Analysis

Upload a PDF medical report.

The AI assistant will:

* Extract report information
* Generate a patient-friendly summary
* Highlight important findings

## Disclaimer

This project is intended for educational and informational purposes only.

It is not a substitute for professional medical advice, diagnosis, or treatment. Always consult a qualified healthcare professional for medical concerns.

## Future Enhancements

* Voice-based symptom input
* Multi-language support
* Doctor recommendation system
* Medical history tracking
* Enhanced report analytics

##

K. Hemanth

G. Pulla Reddy Engineering College
