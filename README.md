# Sentiment-Analysis-On-Yelp-Reviews

#### Introduction
The abundance of Yelp reviews has significantly influenced customer decision
making, especially in the food service industry. This project delves into the intricate 
relationship between the ratings and the corresponding sentiment expressed in Yelp reviews. 
Through sentiment analysis, this project seeks to uncover how quantitative evaluations correlate 
with qualitative feedback, hypothesizing that positive sentiments are associated with higher 
ratings and vice versa. Employing various NLP models such as the Generalized 
Linear Model (GLM), XGBoost Regressor, and Gradient Boost Regressor, the project 
evaluates this relationship using features consisting of review text, rating, and review length to 
predict the sentiment scores. The findings aim to provide deeper insights into consumer 
behavior and enhance understanding of the role of star ratings in reflecting customer 
experiences.

### Dataset
https://www.yelp.com/dataset

### Hypothesis
The project is driven by the hypothesis that a significant relationship exists between the sentiment expressed in Yelp reviews and the star ratings assigned by users. Specifically, it is posited that reviews expressing positive sentiments will correlate with higher star ratings, while negative sentiments will correspond with lower star ratings. This hypothesis aims to explore the extent to which quantitative ratings reflect the qualitative sentiments of consumers.

Null Hypothesis (H0): No significant linear relationship exists between sentiment scores and star ratings. 
Alternative Hypothesis (H1): A significant linear relationship exists between sentiment scores and star ratings. 

Spearman’s rank correlation coefficient was 0.47 with a p-value of 0.0 which negates our null hypothesis. The results suggest a significant relationship between the Rating and Compound 
sentiment score of the reviews. 

### Methodology

The methodology involves cleaning and pre-processing the data to implement and test machine learning models like GLM, XGBoost, and gradient boosting regression on a sample of Yelp reviews to predict sentiment scores. The features are review length, rating, and review text. The predicted sentiment score was compared with the compound score obtained using VADER. Key metrics such as R-squared error, mean squared error (MSE) and mean absolute error (MAE) will be employed to assess model performance. 

The findings of this project are expected to offer valuable insights into consumer behavior and decision-making processes in the context of online reviews. This can translate to enhanced customer engagement and service improvement strategies for businesses. For consumers, it provides a deeper understanding of what star ratings may signify regarding actual customer experience.

### Results

The project successfully established a significant relationship between the sentiment expressed in Yelp reviews and star ratings, thus validating the hypothesis. The sentiment analysis, using VADER, revealed a nuanced understanding of customer feedback, while the machine learning models effectively predicted sentiment scores using user reviews and ratings as features. The models demonstrated varying degrees of performance. XG Boost outperformed Gradient Boost and GLM.

The quantitative relationship between sentiment score and ratings varies across regions, cultures, and sectors (Wan, 2022). The business strategies need to be tailored specifically by analyzing the sentiment of the reviews of the business that is in question. Our findings underscore the complexity of consumer opinions and the efficacy of combining qualitative and quantitative data for a comprehensive understanding. The study contributes to the broader understanding of customer sentiment in online reviews and can assist businesses in leveraging this information for improved customer engagement and service strategies. 
