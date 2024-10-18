# Stock-Sentiment-Analysis

# Stock Sentiment Analysis using News Headlines

This project explores the use of news headlines to predict the next day's impact on a news channel's stock price.

## Dataset

The dataset is a rich combination of world news headlines and corresponding stock price movements. It provides valuable insights into the relationship between news sentiment and market performance.

* **Structure:**
    * Each day in the data frame contains 25 columns representing top news headlines.
    * A binary target variable indicates the stock price movement:
        * Class 1: Stock price increased.
        * Class 0: Stock price remained the same or decreased.

## Approach

The project utilizes a combination of feature extraction techniques and machine learning algorithms to uncover the predictive power of news headlines:

1. **Feature Extraction:**
    * **TF-IDF:** This method focuses on identifying terms that are important within a document but less frequent in the overall corpus. It helps to capture the unique sentiment conveyed by each headline.
    * **Bag-of-Words (BoW):** This approach represents headlines as a simple collection of words, providing a baseline for feature representation.

2. **Machine Learning Models:**
    * **Random Forest Classifier:** This ensemble learning method effectively handles complex relationships and potential noise within the data.
    * **Multinomial Naive Bayes:** This probabilistic classifier leverages the assumption of conditional independence between features, offering a simpler yet informative model.

## Next Steps

This project lays the foundation for further exploration. Potential avenues for improvement include:

* Experimenting with additional feature extraction techniques, such as sentiment analysis tools or named entity recognition.
* Evaluating the performance of other machine learning models, such as Support Vector Machines (SVMs) or deep learning networks.
* Incorporating real-time news data to analyze the impact of current events on stock prices.

This project welcomes contributions. Feel free to fork the repository and suggest enhancements!
