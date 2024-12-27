# Uber_Customers_Review_ML
## Project Title: Uber Customer Reviews Dataset (2024)
## Subtitle: Sentiment Analysis and Insights from 12,000+ Google Play Store Reviews
# DataSet Description
   - This dataset contains over 12,000 customer reviews of the Uber app collected from the Google Play Store.
   - The reviews provide insights into user experiences, including ratings, feedback on services, and developer responses.
   - The data is cleaned and anonymized to ensure privacy compliance and ethical usage.
   - It serves as a valuable resource for sentiment analysis, natural language processing (NLP), and machine learning applications.
## Column Name | Description
 - userName: Anonymized username of the reviewer.
 - userImage: URL of the reviewer's profile image (if available).
 - content: Text content of the review describing the user's experience.
 - score: Numerical rating given by the user (1–5).
 - thumbsUpCount- Number of likes received by the review.
 - reviewCreatedVersion- App version at the time of review creation (if available).
 - at: Timestamp indicating when the review was posted.
 - replyContent: Developer's response to the review (if any).
 - repliedAt: Timestamp indicating when the developer replied (if any).
 - appVersion: App version string associated with the review (if available).
# Data Science Applications
### Sentiment Analysis:
- Classify reviews as positive, neutral, or negative based on score and content.
- Identify trends in customer satisfaction over time.
### Natural Language Processing (NLP):
- Perform topic modeling to uncover themes in customer feedback.
- Generate word clouds to visualize frequently used words in reviews.
### Machine Learning:
- Train a sentiment classification model using review text as input.
- Predict customer satisfaction based on textual feedback.
### Business Insights:
- Analyze user feedback to identify strengths (e.g., "friendly drivers") and weaknesses (e.g., "long wait times").
- Compare app performance across different versions (appVersion).
### Time Series Analysis:
- Track changes in average scores over time using the at column.
- Identify seasonal patterns or anomalies in customer feedback.
### Customer Behavior Analysis:
- Study the correlation between score and thumbsUpCount to understand review impact.
- Analyze the effect of developer replies (replyContent) on customer satisfaction.

# Conclusion:
  - Content is the only feature highly correlated with ScoreSentiment.
  - 4.554.10001 is the top appversion.
  - There is no linear relationship between Score and Thumbs Up Count.
  - The reviews are more encountered during afternoons and in Monday.
  - The peak time is 10PM.
  - "good" is the most used positive review.
  - Model Accuracy high for SupportVectorClassifier with 92.4%.
