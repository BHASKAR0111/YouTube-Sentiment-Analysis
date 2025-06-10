****youtube-sentiment-analysis
Analyze sentiment of YouTube comments using NLP
#  YouTube Comment Sentiment Analysis
**
**This project performs **Sentiment Analysis on YouTube video comments** using the **YouTube Data API** and **Natural Language Processing**. It fetches comments automatically, cleans them, analyzes sentiment using `TextBlob`, and visualizes the results with charts and word clouds.

---

##  Tools & Libraries

- Python
- Jupyter Notebook
- YouTube Data API v3
- pandas
- TextBlob
- seaborn & matplotlib
- WordCloud

---

## Features

-  Automatically fetches top 200 comments using YouTube API  
-  Cleans & preprocesses comment text  
-  Performs sentiment analysis (Positive, Negative, Neutral)  
-  Visualizes sentiment distribution (Bar Chart, Pie Chart)  
-  Generates WordCloud of most frequent words  
-  Displays most positive and negative comments

---

##  Sample Output

>  Bar Chart  
>  Pie Chart  
>  WordCloud  
>  Sentiment Summary & Comment Examples  

*(Add screenshots here if you want)*

---

## How to Run

1. Clone this repo or upload the notebook:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
Open in Jupyter Notebook:

bash
Copy
Edit
jupyter notebook youtube_sentiment_analysis.ipynb
Replace your YouTube API key and video ID at the top of the notebook:

python
Copy
Edit
API_KEY = "YOUR_API_KEY"
video_id = "VIDEO_ID"
Run all cells step-by-step.

YouTube API Setup
To use the YouTube API:

Go to Google Cloud Console

Create a project → Enable YouTube Data API v3

Generate an API key and paste it in the notebook.

 Final Output
At the end, you'll get:

Sentiment distribution % (Positive, Neutral, Negative)

Top 5 most positive comments

Top 5 most negative comments

 Conclusion
Majority of the comments are Positive, indicating a good reception of the video.

Small percentage of Negative or Neutral comments — natural for any popular video.

This project is a great example of using Python + NLP + API integration for real-world insights.

 Author
[Bhaskar Baluni]
 GitHub: @BHASKAR0111

yaml
Copy
Edit

---

##  What To Do Next:

1. Ja apne GitHub repo par → Click `Add file → Create new file → README.md`
2. Is README content ko paste kar de.
3. (Optional) Ek screenshot le notebook ka output ka (graph, pie chart, word cloud) → Upload and link it with:
   ```markdown
   ![Output](output.png)
