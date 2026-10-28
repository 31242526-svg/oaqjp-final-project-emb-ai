# Final Project

Emotion Detection Application — final project of the IBM course
*Developing AI Applications with Python and Flask*.

The application sends a statement to the Watson NLP `EmotionPredict` service
and reports the score of anger, disgust, fear, joy and sadness plus the
dominant emotion.

## Contents

- `EmotionDetection/` — the `emotion_detector()` package
- `server.py` — Flask server and `/emotionDetector` endpoint
- `test_emotion_detection.py` — unit tests
- `templates/`, `static/` — the web page and its script

## Running

```bash
pip install -r requirements.txt
python server.py
