AI-Powered Dyslexia Detection and Assistive Learning System

An intelligent system designed to detect dyslexia through speech, text, and eye movement analysis while offering personalized assistive learning.

Features:

Speech Transcription:

Uses Google Speech API and CMU Sphinx for accurate speech-to-text conversion.

Enhanced text clarity with GPT-4o-mini.

Dyslexia Risk Scoring:

Analyzes text patterns (e.g., repeated words, letter swaps) to calculate dyslexia risk.

Eye movement analysis through video processing.

Image Processing:

Extracts text from images using EasyOCR and OpenCV.

Preprocessing for improved accuracy (contrast, sharpening, noise reduction).

Personalized Learning:

Adaptive quizzes based on the calculated risk score.

Real-time feedback and customized exercises.

User Management:

Secure login and registration with bcrypt encryption.

User data stored in JSON files.

Technologies Used

Backend: Flask, Python

Speech Recognition: Google Speech API, CMU Sphinx

Text Processing: GPT-4o-mini

Image Processing: EasyOCR, OpenCV, PIL

Text-to-Speech: pyttsx3

Data Storage: JSON

Security: bcrypt

Web Framework: Flask

Installation:

Clone the repository:
git clone https://github.com/yourusername/dyslexia-detection.git  
cd dyslexia-detection 

Install dependencies:
pip install -r requirements.txt  

Run the Flask application:
python app.py  

Access the application:
Open your browser and go to http://localhost:5000/

Usage:

Register or login to access the system.

Upload an audio file (.wav), image, or video for analysis.

View the dyslexia risk score and personalized recommendations.

Take quizzes to assess comprehension and track progress.

Folder Structure
graphql

├── FINAL_CODE_last  
│   ├── app.py              # Main application file  
│   ├── templates/          # HTML templates  
│   ├── static/             # CSS and JavaScript files  
│   ├── users.json          # User data storage  
│   ├── temp/               # Temporary file storage  
│   └── requirements.txt    # Dependencies  

Future Enhancements:

Real-time eye tracking using webcam.

Mobile app version for better accessibility.

Support for multiple languages.
