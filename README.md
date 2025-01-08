# <div align="center"> **<span style="font-size:80px;">Clicks, Tricks, and Engagement Kicks!</span>** </div>
### <div align="center"> -------------- *Exploring the Hidden Drivers of Increased User Engagement In Articles & Emails* ----------------
![[alt text](https://github.com/Sandeep-Bansal1/heart_disease/blob/main/heart%20cover%20picture.png?raw=true)](https://github.com/Sandeep-Bansal1/User-Engagement/blob/85d449a5189e14f63d64d3adec626a82f0ed79a3/Images/Wallpaper.webp) 

<pre>
Contrubuter  : Sandeep Bansal
</pre>

<pre>
Languages: Python
Tools/IDE: Anaconda
Libraries: pandas, matplotlib, numpy, sklearn, seaborn, train_test_split,LogisticRegression, accuracy_score, confusion_matrix, classification_report, RandomForestClassifier, GradientBoostingClassifier
</pre>

<pre>

</pre></b>
---
## Buisness Objective </b> 
- **A personal project of mine during my free time** I wanted to investiage whether the use of machine learning, can uncover the patterns that transform a casual reader into a loyal news enthusiast, keeping them engaged from headline in a article or email to deep dive.
- This is a ficticious dataset that was created by the Python Library called Faker. It contains 250,000 rows and 44 attributes

## Background </b> 
- In a fragmented media environment with seemingly endless sources of information to choose from, Americans’ news habits have changed dramatically in the 21st century. Many seem to be dropping the old school daily habit of waking up in the morning to watch the news before work or dropping their child off to school to now checking their smartphones. However, with that being said does checking news via a cellular device increase the chances of a user reading an entire article?
- **Are their other associated factors to consider when determining whether a reader will make it to the bottom of the article?**


## Dataset </b> 
- The Data Dictionary below will help you become familiar with each column and what each of them represent.
![Data Dictionary](https://github.com/Sandeep-Bansal1/User-Engagement/blob/main/DataDictionary/DataDictionary.png?raw=true)


## Exploratory Data Analysis </b>
![Year-over-Year Growth](https://github.com/Sandeep-Bansal1/User-Engagement/blob/main/Images/YOY.png?raw=true)

- *High Growth Periods (April, June, December)*:
  - Significant YoY growth in these months indicates successful content strategies or campaigns. Replicate similar tactics to sustain engagement.

- *Drop in July and November*:
  - Notable declines suggest disengagement during these months. Address this with targeted campaigns, timely content, or seasonal promotions.

- *December Recovery*:
  - Strong recovery after the November dip highlights the effectiveness of holiday-related content. Plan seasonal strategies to capitalize on year-end engagement.

- *Stable Early-Year Engagement (Jan-March)*:
  - Consistent user visits in early months suggest steady consumption habits. Use this time to introduce new features and maintain engagement.


![Users-by_Device-Type](https://github.com/Sandeep-Bansal1/User-Engagement/blob/main/Images/Users_By_Device_Type.png?raw=true)

- *Mobile visits consistently shows higher user engagement*:
  - Mobile is clearly the primary device for users to access news articles, indicating a mobile-first approach is essential for improving user engagement. Ensuring the website is optimized for mobile experiences (responsive design, faster     loading times, and mobile-friendly features) will likely boost retention.

- *Mobile Stability vs. Desktop Volatility*:
  - Mobile visits appear more stable over time compared to desktop visits, which show significant ups and downs throughout the year.
Insight: This highlights the importance of mobile user retention, as mobile users demonstrate more consistent behavior. Mobile engagement should be prioritized in personalization efforts and content strategies to ensure steady user growth.


![Correlation](https://github.com/Sandeep-Bansal1/User-Engagement/blob/main/Images/Correlation.png?raw=true)

- *Breaking News, Notifications, and Social Media Engagement Are the Strongest Drivers*:
  
  - Breaking_News: Users are more likely to engage deeply with articles labeled as "breaking news." Subscribed_To_Notifications: Users who opt into notifications are more engaged and likely to finish articles. Follows_On_Social_Media: Users who follow the brand on social media platforms tend to engage more deeply with content.
 
- *Form Submissions and Comments Are Strong Indicators of Engagement*:

  - Features like Form_Submissions and Comments show a significant positive correlation with users reaching the bottom of an article

## Proposed Methodology </b>
- Since our dataset includes a binary target column called **`Reached_Bottom_of_Article`**, which indicates whether a user scrolled to the end of a news article, we will apply several classification machine learning models to predict this behavior. The models we plan to use include **Logistic Regression**, **Random Forest**, **XGBoost**, and **Gradient Boosting**.
- These algorithms are well-suited for binary classification problems, where the goal is to determine the likelihood that a user fully engages with an article. By comparing the performance of these models, we aim to identify the most effective approach for predicting user engagement with news content.

## Preliminary Results </b>

![Preliminary Results](https://github.com/Sandeep-Bansal1/User-Engagement/blob/main/Images/Scores.png?raw=true)


![AUC Sore](https://github.com/Sandeep-Bansal1/User-Engagement/blob/main/Images/AUC_SCORE.png?raw=true)


## Next Steps </b>
- Utilize Natural Language Processing to tokenize and remove stop words to ultimately convert text from **`Article`** and **`Heading`** to Numerical values to see if that makes a difference.
- Click Here: [NLP_EDA](https://github.com/Sandeep-Bansal1/User-Engagement/blob/bcbdc7d40edb5377fa86f464deb62911778b6044/NLP/NLP.ipynb) to see NLP work done so far.
- Here's a fun word cloud I made comparing most popular words used in Business Articles vs Sports ![Word Cloud](https://github.com/Sandeep-Bansal1/User-Engagement/blob/main/Images/WordCloud_by_NewsType.png?raw=true)
