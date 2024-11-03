# YouTube Videos Data Analytics

This project retrieves data about YouTube videos using the Google API, performs exploratory data analysis (EDA) and visualizations, and builds machine learning models to gain insights into viewership trends and other metrics.

## Workflows
1. **Data Retrieval**: Fetch data from YouTube using the Google API, including information like views, likes, comments, and more.
2. **Exploratory Data Analysis (EDA)**: Analyze and visualize the data.
3. **Machine Learning Model**

## Prerequisites
- Python 3.11
- Install required packages by running:
  ```bash
  pip install -r requirements.txt

## Setup and Installation
1. **Get Google API Key**: Register for a YouTube API key from the [Google Cloud Console](https://console.cloud.google.com/).
2. **Environment Variables**: Create a `.env` file in the project’s root directory to store the API key. The file should look like this:
   ```makefile
   API_KEY=your_youtube_api_key_here
