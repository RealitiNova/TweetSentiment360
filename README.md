# TweetSentiment360

**TweetSentiment360** is a sentiment analysis app that classifies tweets into **Positive**, **Neutral**, or **Negative** categories. This tool is built using Natural Language Processing (NLP) and machine learning, making it ideal for analyzing public opinions on social media.

## Features
- **Real-Time Tweet Analysis**: Enter any tweet and get immediate feedback on its sentiment.
- **User-Friendly Interface**: Powered by Streamlit, the app is intuitive and easy to use.
- **Fast and Accurate Predictions**: Achieved 88% accuracy on the test dataset.

## How to Use
1. Visit the deployed app at **[TweetSentiment360](https://example.streamlit.app)**. 
2. Input a tweet into the text box.
3. Click **Analyze** to see if the sentiment is **Positive**, **Neutral**, or **Negative**.

## Project Workflow
1. **Dataset Preprocessing**:
   - Cleaned raw tweets by removing URLs, hashtags, mentions, and special characters.
   - Tokenized and lemmatized text to normalize the language.
2. **Feature Engineering**:
   - Used **TF-IDF Vectorization** to convert text into numerical features.
3. **Model Training**:
   - Trained a **Logistic Regression** model for sentiment classification.
   - Fine-tuned hyperparameters using GridSearchCV.
4. **Deployment**:
   - The app is deployed using Streamlit for easy access and interaction.

## Installation Guide
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/RealitiNova/TweetSentiment360.git
