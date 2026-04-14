# AI-Based Emotion Detection System

## Project Overview

This is a full-stack software engineering project that develops an AI-based web application to detect emotions in text. The application leverages the **IBM Watson NLP library** for analysis and uses **Flask** for web deployment.

## Technical Stack

- **Language:** Python 3.x
- **Framework:** Flask (Web Server)
- **AI Service:** Watson NLP (Emotion Detection)
- **Frontend:** Modern Glassmorphism (HTML/CSS/JS)
- **Testing:** Unittest (Python)
- **Code Quality:** Pylint (Static Analysis)

## Features

- **Real-time Analysis:** Detects anger, disgust, fear, joy, and sadness.
- **Dominant Emotion Identification:** Automatically highlights the primary emotion.
- **Error Handling:** Gracefully handles invalid inputs and connection timeouts.
- **Modular Packaging:** Encapsulated as a reusable Python package.

## Project Structure

- `EmotionDetection/`: Logic for interacting with Watson NLP.
- `static/`: Frontend assets (CSS/JS).
- `templates/`: HTML interface.
- `server.py`: Flask application runner.
- `test_emotion_detection.py`: Unit tests.
