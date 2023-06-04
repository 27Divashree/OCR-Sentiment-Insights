# Text-Mood-Analyzer
A sentiment analysis web app to analyze sentiments by extracting text using ocr.


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

## Usecases
### Customer Feedback Analysis
Businesses can leverage the OCR Sentiment Analysis project to analyze customer feedback from surveys, reviews, or support tickets. By extracting text from the feedback documents and performing sentiment analysis, businesses can gain insights into customer sentiment. They can identify recurring positive or negative sentiments, identify areas for improvement, and make data-driven decisions to enhance their products or services.

### Opinion Mining in Politics or Public Sentiment
The project can be applied to analyze political speeches, news articles, or public opinion expressed in text. By extracting text using OCR and performing sentiment analysis, it becomes possible to understand the sentiment associated with political figures, policies, or societal issues. This information can help political campaigns, policymakers, or researchers to gauge public sentiment, identify concerns, and assess the impact of political decisions.

By combining OCR technology with sentiment analysis, the OCR Sentiment Analysis project provides a valuable tool for extracting insights from text data. It enables businesses, organizations, researchers, and individuals to understand sentiment, make informed decisions, and take appropriate actions based on the sentiment expressed in the extracted text.


