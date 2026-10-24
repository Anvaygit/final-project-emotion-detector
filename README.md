# Final Project - Emotion Detector

An AI-based web application that detects emotions from text using the Watson NLP library and Flask.

## Features
- Detects 5 basic emotions: anger, disgust, fear, joy, and sadness.
- Identifies the dominant emotion from user text.
- Interactive web interface deployed using Flask.
- Robust error handling for blank/invalid inputs.
- High code quality adhering to PEP8 standards (10.00/10 pylint score).

## Application Package
The core functionality is packaged under `EmotionDetection` with `emotion_detector` function.

## How to Run
1. Install dependencies: `pip install flask requests`
2. Run unit tests: `python test_emotion_detection.py`
3. Start the Flask server: `python server.py`
4. Access the web app at `http://127.0.0.1:5000/`
