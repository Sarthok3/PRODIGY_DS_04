# **VISUAL INSIGHTS INTO SOCIAL MEDIA CONVERSATIONS AND SENTIMENTS** #

The code performs exploratory data analysis (EDA) and visualization on a Twitter dataset containing text messages, topics, and sentiment labels. Below are the key steps involved:

**1. Data Loading and Cleaning:**
- Reads the CSV file containing Twitter training data.
- Assigns column names (`ID`, `Topic`, `Sentiment`, `Text`).
- Checks for and removes null and duplicate entries.

**2. Basic Statistics and Information:**
- Prints dataset shape, description, and unique sentiment labels.
- Verifies data integrity by ensuring no null or duplicate values remain.

**3. Data Visualization:**
- Bar Plot: Shows the count of topics using `barh`.
- Count Plot: Displays sentiment distribution using `countplot`.
- Pie Chart: Visualizes sentiment percentages.
- Topic-Sentiment Count: Bar plots for top 5 topics across Negative, Neutral, and Irrelevant sentiments.

**4.Google Topic Analysis:**
Filters data for the "Google" topic and visualizes its sentiment distribution using a pie chart.

**5. Message Length Analysis:**
- Adds a new feature `msg_len` to store text length.
- Visualizes message length distribution and box plots by sentiment.

**6.Cross-tabulation and Heatmap:**
Creates a heatmap showing the relationship between topics and sentiment counts.

**7.WordCloud Generation:**
Creates two WordClouds:
- One for topic keywords.
- One for all text messages in the corpus.

## **Key Objective:** ##
The key objective is to analyze and visualize social media conversations and sentiments, identify trends across topics, explore message lengths, and reveal patterns through distribution charts, bar plots, heatmaps, and word clouds for better insights.
