# iPhone Reviews Sentiment Analysis

##**Project Overview**
This project focuses on analyzing user reviews for iPhones by combining methodologies from two research papers. The goal is to extract meaningful insights into customer sentiment, preferences, and areas for improvement. Using **VADER** for sentiment analysis and exploratory data analysis (EDA), we categorized reviews into positive and negative sentiments, visualized trends, and highlighted features driving user feedback.

**Key Features**
1. Sentiment Analysis:

Classified user reviews as Positive or Negative using the VADER tool.
Visualized sentiment distribution across countries and product variants.

2. Exploratory Data Analysis (EDA):

Used user ratings to identify trends like average ratings by country and product variant.
Examined user preferences and broader patterns in the dataset.

3. Wordcloud Analysis:

Created Wordclouds to identify frequently used words in reviews.
Distinguished between positive and negative sentiments to analyze product features.

4. Model Training:

Trained multiple classification models to predict sentiment, achieving the highest accuracy (88%) with SVM.


**Methodology**
Data Collection: iPhone_reviews dataset from Kaggle.
Data Preprocessing: Removed punctuation, numbers, and tokenized text to ensure data reliability.
Sentiment Analysis: Applied VADER sentiment scoring to classify reviews into positive or negative.
Localization: Grouped reviews by geographic location and product variants to identify trends.
Result Interpretation: Analyzed sentiment trends and visualized data insights using Wordclouds and sentiment-specific counts.

**Tools and Libraries**
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, NLTK, Wordcloud, collections.counter.
Sentiment Analysis Tool: VADER for sentiment classification.

**Algorithms and Techniques**
**1. Classification Algorithms:**

Logistic Regression, Random Forest, Naive Bayes, and SVM.
SVM achieved the highest accuracy (88%).

**2. Word Frequency Analysis:**

Counted occurrences of words in positive and negative reviews to identify sentiment trends.

**3. Wordcloud Generation:**

Visualized frequent words in positive and negative reviews for exploratory analysis.

**Insights and Findings**

**1. Key Insights:**

Features like Camera, Battery, and Performance received predominantly positive reviews.
Features such as Heating, Service, and Charging had mixed reviews, indicating areas for improvement.

**2. Sentiment Breakdown:**

Positive Sentiments: Camera (82%), Performance (87%), Display (86%), Quality (79%), and Battery (76%).
Negative Sentiments: Heating (50%), Working (46%), and Service (49%).

**3. Feature Analysis:**

Grouped features like Battery, Camera, Heating, and others to analyze the count of positive and negative sentiments.
Identified actionable insights for improvement in areas like Heating and Service.

**Conclusion**
This analysis provides valuable insights into customer sentiment, helping businesses identify areas for improvement and better align with user preferences. The combination of sentiment analysis, data visualization, and model training underscores the power of data-driven decision-making.
