# Text-Mood-Analyzer
A sentiment analysis app to extract text using ocr.


This web app utilizes the EasyOCR library to perform Optical Character Recognition (OCR) on input images and extracts the text. The extracted text is then analyzed for sentiment using the Natural Language Toolkit (NLTK) library. The app predicts whether the text is positive or negative and provides the sentiment analysis result to the user.

## Features

- Upload an image containing text
- Perform OCR to extract text from the image
- Analyze the sentiment of the extracted text
- Predict whether the text is positive or negative

## Technologies Used

- Flask: A web framework used for building the web app
- EasyOCR: A library for OCR that supports multiple languages and provides accurate text extraction from images
- NLTK: A natural language processing library used for sentiment analysis
- -SentimentAnalysisAPI: Powerful tool that classifies text as either positive or negative, providing valuable insights into the sentiment expressed in the text. By leveraging natural language processing algorithms, the API analyzes the content and assigns a sentiment label, allowing businesses and developers to gain a deeper understanding of customer opinions, reviews, and social media sentiments. With its ease of use and high accuracy, the Sentiment Analysis API streamlines the process of sentiment classification, enabling businesses to make data-driven decisions and enhance customer satisfaction.

## Prerequisites

- Python 3.7 or higher
- Flask and its dependencies
- EasyOCR library
- NLTK library

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/ocr-sentiment-analysis-web-app.git
   ```

2. Install the required libraries:

   ```bash
   pip install flask easyocr nltk
   ```

3. Download the necessary NLTK data:

   ```python
   import nltk

   nltk.download('vader_lexicon')
   ```

## Usage

1. Run the Flask development server:

   ```bash
   flask run
   ```

2. Access the web app through your browser:

   ```text
   http://localhost:5000
   ```

3. Upload an image containing text using the provided button.
4. The app will perform OCR on the image and extract the text.
5. The extracted text will be analyzed for sentiment using NLTK.
6. The app will display the sentiment analysis result, indicating whether the text is positive or negative.

