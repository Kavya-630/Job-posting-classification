# Emotion Classifier Using SVM

## Overview
This project develops an emotion classification model that predicts the emotion of a given text using a Support Vector Machine (SVM) classifier with TF-IDF vectorization. The model is trained on a dataset labeled with emotions such as joy, sadness, anger, fear, love, and surprise.

## Features
- **Text Preprocessing:** This includes cleaning the text by removing punctuation, stopwords, URLs, and digits.
- **TF-IDF Vectorization:** The text data is transformed using the TF-IDF method.
- **Emotion Classification:** The emotions are classified using the LinearSVC (Support Vector Machine) algorithm.
- **Evaluation:** The model's performance is assessed using accuracy scores, classification reports, and visualizations of the confusion matrix.

## Usage
Make sure your dataset CSV file (e.g., `emotions.csv`) is located in the project directory, or update the file path in `main.py`.

To run the main script, use the following command:
```bash
python main.py
```

### Results
Example accuracy: ~79.7%
