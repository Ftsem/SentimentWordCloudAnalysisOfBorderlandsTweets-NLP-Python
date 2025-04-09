
# Sentiment & Word Cloud Analysis of Borderlands Tweets

This project analyzes tweets about the popular game *Borderlands* to determine the general sentiment of the community. It uses sentiment analysis and word cloud visualization to provide insights into player feedback.

## Dataset

The dataset contains over 2000 tweets about *Borderlands*. The data was preprocessed to remove duplicates, null values, mentions, and special characters.

## Methods

### Sentiment Analysis
The sentiment of each tweet was analyzed using the **TextBlob** library. Tweets were classified as **positive**, **negative**, or **neutral** based on the polarity score.
In the following the pie chart that shows the sentiment distribution of the tweets:

Positive tweets: 56.1%

Negative tweets: 26.6%

Neutral tweets: 17.3%
![](https://github.com/Ftsem/SentimentWordCloudAnalysisOfBorderlandsTweets-NLP-Python/blob/9c571143e5b50f13b9a68d6ee8dc1130afa87d4e/Assets/Screenshot%202025-04-09%20143351.png)

### Word Cloud Generation
**WordCloud** was used to generate visual representations of the most frequent words in positive and negative tweets.

# Positive Tweets Word Cloud Analysis
- Positive Tweets Word Cloud:
  ![Positive Tweets Word Cloud](https://github.com/Ftsem/SentimentWordCloudAnalysisOfBorderlandsTweets-NLP-Python/blob/9c571143e5b50f13b9a68d6ee8dc1130afa87d4e/Assets/Screenshot%202025-04-09%20143420.png)

  
### Frequent Keywords:
The word "borderland" appears prominently, indicating a strong connection to the game. Other words like "thank," "love," "excited," "played," "fun," and "good" suggest a positive and enthusiastic response from users.

### Key Themes:
Most of the tweets in this category are expressing excitement and enjoyment related to the game. Words such as "stream," "play," "character," and "dlc" (downloadable content) show that users are talking about the game's features and their experiences.

### Sentiments:
Overall, the sentiment is positive, and users seem to be sharing their excitement and happiness about the game.

# Negative Tweets Word Cloud Analysis
- Negative Tweets Word Cloud:
  ![Negative Tweets Word Cloud](https://github.com/Ftsem/SentimentWordCloudAnalysisOfBorderlandsTweets-NLP-Python/blob/9c571143e5b50f13b9a68d6ee8dc1130afa87d4e/Assets/Screenshot%202025-04-09%20143430.png)

### Frequent Keywords:
Words like "hate," "fucking," "shitty," and "fuck" dominate, indicating strong frustration. Other terms such as "crashes," "problems," "xbox," "pc," and "back" suggest issues related to technical problems or the gaming platform.

### Key Themes:
Many of the tweets seem to express dissatisfaction with the technical aspects of the game, including crashes, bugs, or issues with gameplay, especially on platforms like PC and Xbox. "Fix," "stream," "game," and "video" indicate that players are calling for improvements.

### Sentiments:
The sentiment here is negative, with users expressing frustration over technical difficulties and their gaming experience.

---


# Key Insights

- The positive tweets reflect enjoyment and excitement about playing the game, with a focus on features, gameplay, and community interaction.
- The negative tweets focus more on issues such as bugs, crashes, and frustrations with the game’s technical performance.

---

# Recommendations

- **For game developers or community managers**: This analysis can be used to understand the core issues affecting user experience (technical problems in negative tweets) and the aspects players enjoy (fun, characters, gameplay in positive tweets).
  
- **For marketing strategies**: Promote positive experiences while addressing the common issues raised in negative tweets to improve customer satisfaction.
