**#  YouTube Comment Sentiment Analysis

Analyze sentiment of YouTube comments using NLP, TextBlob, and visualizations.
**
This project performs **Sentiment Analysis on YouTube video comments** using the **YouTube Data API** and **Natural Language Processing**. It fetches comments automatically, cleans them, analyzes sentiment using TextBlob, and visualizes the results using bar chart, pie chart, and word cloud.

---

## Tools & Libraries Used

- Python
- Jupyter Notebook
- YouTube Data API v3
- pandas
- TextBlob
- seaborn & matplotlib
- WordCloud

---

##  Features

-  Automatically fetches top 200 comments using the YouTube API  
-  Cleans & preprocesses comment text  
-  Performs sentiment analysis: **Positive**, **Negative**, or **Neutral**  
-  Visualizes sentiment distribution (Bar Chart & Pie Chart)  
-  Generates WordCloud of most frequent words  
-  Displays top 5 most positive & most negative comments  

---

## Sample Output

  
>  Sentiment Bar Chart  
>  Pie Chart  
>  Word Cloud  
>  Sentiment Summary & Sample Comments  

---

##  How to Run

1. **Clone this repository** or upload the `.ipynb` notebook manually:


git clone https://github.com/BHASKAR0111/youtube-sentiment-analysis.git
Open the notebook:

jupyter notebook youtube_sentiment_analysis.ipynb
Replace placeholders at the top of the notebook:

API_KEY = "YOUR_API_KEY"
video_id = "YOUR_VIDEO_ID"
Run all cells step by step.

 YouTube API Setup
To use the YouTube API:

Go to Google Cloud Console

Create a new project

Enable YouTube Data API v3

Generate an API key

Paste it in the notebook:

API_KEY = "YOUR_API_KEY"
 Note: Don’t share your API key publicly. Remove it before uploading your notebook to GitHub.

 Final Output Includes:
Sentiment distribution: % of Positive, Neutral, and Negative comments

Top 5 most positive comments

Top 5 most negative comments

Bar chart, pie chart, and word cloud for visualization

 Conclusion
Majority of comments are Positive, indicating a good reception of the video.

Few Neutral or Negative comments are expected for any public content.

This project demonstrates real-world NLP using Python, APIs, and visual analytics.

 Author
Bhaskar Baluni
GitHub: @BHASKAR0111
