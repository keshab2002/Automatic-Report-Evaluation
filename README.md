# Automatic Student Report Evaluation

## Overview
This project is an **image processing and NLP (Natural Language Processing) application** designed to **automatically evaluate student reports** based on **keyword analysis**. It processes handwritten and digital reports, extracts content, and assesses them based on relevance, clarity, completeness, and uniqueness.

## Features
- **OCR for Handwritten Reports**: Extracts text from scanned or photographed reports.
- **NLP for Report Evaluation**:
  - Keyword Matching
  - Topic Modeling
  - Plagiarism Detection
  - Grammar & Readability Analysis
  - Sentiment & Context Analysis
- **Automated Scoring & Categorization**:
  - Relevance (Topic Match)
  - Clarity (Grammar & Readability)
  - Completeness (Keyword Coverage)
  - Uniqueness (Plagiarism Check)
- **Detailed Reporting**: Generates evaluation reports with feedback.

## Solution Approach
### 1. Image Processing (For Handwritten Reports)
- Use **Tesseract OCR** or **Google Vision API** to extract text.
- Preprocess images (noise removal, contrast enhancement, binarization).

### 2. NLP for Report Evaluation
- **Keyword Matching**: Identifies essential words related to the topic.
- **Topic Modeling**: Uses **TF-IDF, LDA, or BERT** to evaluate topic relevance.
- **Plagiarism Detection**: Compares reports with a database using APIs like Turnitin.
- **Grammar & Readability Analysis**: Uses **spaCy, Grammarly API, or GPT-based models**.
- **Sentiment & Context Analysis**: Evaluates the depth and explanation quality.

### 3. Categorization & Scoring
The system assigns scores based on:
- **Relevance**: How well the report matches the given topic.
- **Clarity**: Grammar, spelling, and readability assessment.
- **Completeness**: Presence of required keywords.
- **Uniqueness**: Plagiarism check.

### 4. Output & Reporting
- Generates a **detailed feedback report** with scores and suggestions.
- Visualizes results using **graphs and charts**.

## Tech Stack
- **OCR**: Tesseract OCR, OpenCV
- **NLP**: spaCy, NLTK, BERT, GPT
- **Plagiarism Detection**: Turnitin API or open-source alternatives
- **Backend**: Python (Flask/Django)
- **Frontend**: React/Flask UI
- **Database**: PostgreSQL, Firebase


## Next Steps
- Define evaluation criteria and keyword sets for different topics.
- Choose and implement OCR for handwritten reports.
- Develop an NLP pipeline for keyword matching and evaluation.
- Create a scoring algorithm.
- Build a simple UI for student report submission and evaluation.

##Contributors
-Keshab Dey
-Manojit Pal
-Shrestha Karmakar
-Churamani Kumar

## Contributing
Pull requests are welcome! If you have suggestions, feel free to create an issue or submit a PR.


