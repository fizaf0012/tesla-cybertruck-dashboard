 Social Media Analytics on Tesla Cybertruck
 
link to tableau public dashboard: 

https://public.tableau.com/app/profile/fiza.fatima8695/viz/Tesla-CyberTruckRedditPosts/Dashboard3
📌 Project Overview

This project analyzes Reddit discussions on the Tesla Cybertruck to uncover public sentiment, key topics, and engagement trends.
The workflow covers the entire NLP pipeline – from data collection to visualization – and presents insights useful for marketing, PR strategies, and community engagement analysis.

🎯 Objectives

-> Collect social media data related to Tesla Cybertruck.

-> Clean and preprocess unstructured text data.

-> Perform sentiment analysis (Positive, Neutral, Negative).

-> Extract keywords and discussion topics using TF-IDF and LDA.

-> Visualize insights in Tableau dashboards (with mockups designed in Figma).

-> Provide business-level insights on what drives the community discussion.

🛠 Tools & Technologies

-> Python (Pandas, TF-IDF, VADER, Scikit-learn)

-> Reddit API (PRAW) – for data collection

-> Tableau / Figma – for visualization and dashboard mockup

-> VS Code – development environment

📂 Dataset

-> Source: Reddit (technology, elonmusk, teslamotors, cars subreddits).

-> Size: ~667 posts.

Columns:

-> title, content, score, num_comments, author, subreddit, created, date

-> Preprocessed: cleaned_content, Lemmatized_Text

-> Sentiment: sentiment_score, sentiment_label

-> NLP: all_keywords, topic, topic_label

🔍 Methodology / Workflow

-> Data Collection – Fetched Reddit posts with PRAW.

-> Data Cleaning – Removed URLs, mentions, emojis, stopwords, and normalized text.

-> Sentiment Analysis – Applied VADER for polarity scoring and labeling.

-> Keyword Extraction – Used TF-IDF to extract frequent keywords.

-> Topic Modeling – Applied LDA to categorize discussion into meaningful themes.

-> Visualization – Built Tableau dashboards with:

  -> Sentiment distribution

  -> Sentiment trends over time
  
  -> Word cloud of top keywords
  
  -> Topic/category trends
  
  -> Engagement metrics (comments, upvotes, influencers)
