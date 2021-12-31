# google-play-store-apps-eda

🔎 Data cleaning and exploratory data analysis done on a data set containing info about apps in 📱 Google Play Store.

Here [Google Play Store Apps](https://www.kaggle.com/lava18/google-play-store-apps) by [@Lavanya](https://www.kaggle.com/lava18) from [Kaggle](https://www.kaggle.com/) is used.

The data source contains 2 CSV files namely `googleplaystore.csv` and `googleplaystore`.

- **googleplaystore.csv** - It has details of the applications on Google Play. There are 13 features which describes a given sample.
- **googleplaystore_user_reviews.csv** - This file contains the first `most relevant` 100 reviews for each app. Each review text/comment has been pre-processed and attributed with 3 new features - Sentiment, Sentiment Polarity and Sentiment Subjectivity.

For this project only `googleplaystore.csv` data is used.

## Info about data cleaning and EDA

### Data cleaning

- 🎯 Missing data
- 👓 Duplicate samples
- 💎 Transforming the data into right data type and shape, also creating new features for ease of woring
- 🎃 Text clening

### EDA

- 🗿 Variable's distribution and its significance with other features
- 🔮 Identifying and dealing with outliers
- 💡 Relations between continuous-to-continuous, categorical-to-categorical and continuous-to-categorical is identifyed by hypothesis testing and various graphs
- 🎸 Simple text analysis

## Todos

- Display findings in README.md
- Use `googleplaystore_reviews.csv` with transformed data set and perform EDA
- Do data imputation on features with unknown values.
