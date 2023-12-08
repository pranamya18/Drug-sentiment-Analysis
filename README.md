# Drug-sentiment-Analysis

The project aims to perform sentiment analysis on drug reviews using transformers to determine patients' behaviors towards various  medicines, products & treatments and predict whether they are positive, neutral or negative. We have implemented Transformers (BioBERT from Hugging Face) and VADER model for sentiment analysis and 
CNN with pre-trained GolVe word embeddings

The Drug Review Dataset is taken from the UCI Machine Learning - Drug Review Dataset. This Dataset provides patient reviews on specific drugs along with related conditions and a 10-star patient rating reflecting the overall patient satisfaction. The data was obtained by crawling online pharmaceutical review sites. The Drug Review Data Set has 7 features including the review and 161,297 Data Points or entries.
 we decided to separate the reviews into positive, negative and neutral sentiments based on ratings score-

Positive Rating >= 7 
Neutral Rating = 5 or 6,
Negative Rating <= 4
