# Sentiment Analysis with TextBlob and Twitter API

Welcome to the **Sentiment Analysis with TextBlob and Twitter API** project! This repository demonstrates how to use Python to fetch tweets from Twitter, clean the text data, and perform sentiment analysis using **TextBlob**.

## Project Overview

Sentiment analysis helps us identify emotions expressed in text data. In this project, you'll learn how to:
- Authenticate with the Twitter API to fetch tweets.
- Preprocess and clean tweet text by removing unnecessary elements like URLs, mentions, and retweets.
- Use **TextBlob** to determine the sentiment of each tweet, measuring both polarity and subjectivity.

## Features

- Real-time tweet fetching using **Tweepy**.
- Data cleaning and preprocessing to make the text ready for analysis.
- Sentiment analysis that provides insights into the polarity and subjectivity of the tweets.

## Getting Started

### Prerequisites

Before you start, ensure you have:
- Python 3.x installed.
- A Twitter Developer account to access the Twitter API.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/divyagoyal002/Sentiment-Analysis.git
   cd Sentiment-Analysis
2. Install the required Python packages:
   ```
   pip install tweepy textblob dotenv

3. Create a .env file in the project directory and add your Twitter API credentials:
   ```
   TWITTER_API_KEY=your_api_key
   TWITTER_API_SECRET_KEY=your_api_secret_key
   TWITTER_ACCESS_TOKEN=your_access_token
   TWITTER_ACCESS_TOKEN_SECRET=your_access_token_secret
   
## Project Structure

- sentiment_analysis.py: The main Python script for fetching and analyzing tweets.
- .env: A file containing environment variables for API credentials (not included for security reasons).
- requirements.txt: A list of project dependencies for easy installation.
Future Improvements

#### Here are some ideas for enhancing the project:

- You can dd data visualization to better illustrate the analysis results.
- Implement more advanced text preprocessing techniques.
- Increase the number of tweets fetched to analyze larger datasets for better insights.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Contributing

Contributions are welcome! 

## Contact

If you have any questions, feedback, or suggestions, please reach out to me at *divyagoyalbg@gmail.com* . I'd love to hear from you!
