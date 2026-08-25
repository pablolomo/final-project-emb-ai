# Repository for final project
# Final Project — Emotion Detector

AI-based web application that detects emotions in text using the Watson NLP `EmotionPredict` library, exposed via a Flask web server.

## Project structure

```
final_project_emotion_detector/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Run

```bash
python3 server.py
```
Then open http://localhost:5000

## Test

```bash
python3 test_emotion_detection.py
```

## Static analysis

```bash
pylint server.py
```
