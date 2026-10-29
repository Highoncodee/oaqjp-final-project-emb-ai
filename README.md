# Emotion Detection Application

## Overview
This project is a web-based Emotion Detection Application that analyzes text and identifies five emotions: anger, disgust, fear, joy, and sadness. It uses the IBM Watson NLP Emotion Detection service and a Flask web application.

## Features
- Detects five emotions from user-provided text.
- Identifies the dominant emotion.
- Provides a simple web interface for entering text.
- Handles empty input with an error message.
- Includes unit tests for the emotion detection module.

## Technologies Used
- Python
- Flask
- Requests
- IBM Watson NLP Emotion Detection API
- HTML, CSS, and JavaScript
- Unittest

## Project Structure

```text
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Highoncodee/oaqjp-final-project-emb-ai.git
   ```

2. Navigate to the project directory:

   ```bash
   cd oaqjp-final-project-emb-ai
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Run the Application

Start the Flask server:

```bash
python server.py
```

Open the following address in your browser:

```text
http://127.0.0.1:5000
```

Enter a sentence and click **Detect Emotion** to view the emotion analysis.

## Run Tests

Run the unit tests with:

```bash
python -m unittest discover -s . -p "test_emotion_detection.py"
```

## Error Handling

The application validates empty input and displays an error message when no text is provided. It also handles errors returned by the emotion detection service.

## Author

Created as part of the IBM Applied AI / Emotion Detection project.
