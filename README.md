**YouTube Comment Sentiment Analyzer**

---

### Introduction
This Python script analyzes sentiments of comments on YouTube videos using two different sentiment analysis models: VADER (Valence Aware Dictionary and sEntiment Reasoner) and RoBERTa (Robustly optimized BERT approach). It retrieves comments from a specified YouTube video, categorizes them into sentiment categories (e.g., positive, negative, neutral), and generates visualizations such as pie charts and word clouds to represent the sentiment distribution and common words used in comments.

### Features
- Retrieves comments from a YouTube video using the YouTube Data API.
- Analyzes sentiments of comments using both VADER and RoBERTa sentiment analysis models.
- Categorizes sentiments into predefined categories (e.g., very positive, positive, neutral, negative, very negative).
- Generates a pie chart to visualize the distribution of sentiment categories.
- Generates a word cloud to visualize the most common words used in comments.
- Saves the sentiment analysis results to a CSV file for further analysis.

### Requirements
- Python 3.x
- Required Python packages: `google-api-python-client`, `oauth2client`, `vaderSentiment`, `transformers`, `matplotlib`, `wordcloud`, `urllib3`

### Usage
1. Make sure you have the necessary Python packages installed. You can install them using pip:
   ```
   pip install google-api-python-client vaderSentiment transformers matplotlib wordcloud urllib3
   ```
2. Obtain API credentials from the Google Cloud Console and save them to a JSON file.
3. Replace the placeholder API credentials file path (`'/content/lisa-420710-b825ec3155d8.json'`) with your actual API credentials file path.
4. Run the script and provide the YouTube video link when prompted:
   ```
   python youtube_sentiment_analyzer.py
   ```
5. The script will retrieve comments from the specified YouTube video, analyze their sentiments, generate visualizations, and save the results to a CSV file.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Acknowledgements
- This script utilizes the YouTube Data API to retrieve comments from YouTube videos.
- The sentiment analysis is performed using the VADER sentiment analysis model developed by C.J. Hutto and the RoBERTa sentiment analysis model provided by the Hugging Face Transformers library.
- Visualizations are created using the Matplotlib and WordCloud libraries.

### Author
[Neeyal D]

