# Android App Market Analysis

## Overview
This project conducts an in-depth analysis of the Android app market using a dataset sourced from the Google Play Store. The dataset encompasses various attributes of apps, including categories, ratings, reviews, installs, prices, and user sentiments. Through rigorous exploration and analysis, the project aims to uncover insights that can inform strategic decisions for app developers, marketers, and businesses operating in the mobile app industry.

## Dataset
The dataset comprises two primary files:
- `apps.csv`: Contains comprehensive details of applications available on Google Play, encompassing 13 descriptive features for each app.
- `user_reviews.csv`: Contains a wealth of user reviews for each app, along with sentiment analysis attributes such as polarity and subjectivity scores.

## Project Tasks
1. **Data Cleaning**: Thoroughly clean the dataset to address issues such as missing values, inconsistent formatting, and special characters.
2. **Correcting Data Types**: Ensure data types are appropriate for analysis by converting columns like 'Installs' and 'Price' to numeric types.
3. **Exploring App Categories**: Investigate the distribution of apps across different categories to identify prevalent trends and patterns.
4. **Distribution of App Ratings**: Analyze the distribution of app ratings and their impact on user perception and app success.
5. **Size and Price Analysis**: Explore the relationship between app size, price, and user sentiment to understand pricing strategies and user preferences.
6. **App Category vs. Price**: Examine how app categories influence pricing strategies and user willingness to pay.
7. **Popularity of Paid vs. Free Apps**: Investigate the popularity and sentiment of paid versus free apps to understand user preferences and behavior.
8. **Sentiment Analysis of User Reviews**: Conduct sentiment analysis on user reviews to uncover insights into user perceptions and satisfaction levels.

## Insights
- Strong positive correlation between app installs and reviews, indicating that higher app installs lead to more user reviews.
- App price exhibits a slight negative correlation with ratings, reviews, and installs, suggesting that higher-priced apps may experience lower user engagement.
- Higher app ratings tend to correlate with increased app installs and user reviews, highlighting the importance of maintaining high-quality app experiences.

## Conclusion
This project provides valuable insights into the dynamics of the Google Play Store app market, offering actionable recommendations for app developers, marketers, and businesses seeking to optimize their app strategies. By leveraging the findings from this analysis, stakeholders can make informed decisions to enhance app performance, user satisfaction, and overall business success.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## How to Use
1. Clone this repository to your local machine.
2. Install the required Python libraries (`pandas`, `matplotlib`, `seaborn`).
3. Run the Jupyter Notebook to explore the analysis and insights.

## Contributors
- Vandesh Sawant

## Code References

I would like to acknowledge the following sources for providing code snippets that were used in this project:

- [San13deep/Play-Store-App-Review-Analysis](https://github.com/San13deep/Play-Store-App-Review-Analysis)
- [step-by-step Android App market analysis](https://www.kaggle.com/code/asmaabdolahpoor/step-by-step-android-app-market-analysis)
