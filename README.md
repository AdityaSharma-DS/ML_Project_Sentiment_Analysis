<h1>Sentiment Analysis </h1>
    This project focuses on sentiment analysis regarding the problems of major U.S. airlines using Twitter data. The dataset was scraped in February 2015 and includes tweets categorized as positive, negative, or neutral, along with categorization of negative reasons.

<h2>Dataset:</h2>
   - The project is from a dataset from Kaggle.
   - Link to the Kaggle project site:https://www.kaggle.com/crowdflower/twitter-airline-sentiment
   - The dataset can be downloaded from the above Kagglewebsite. or you can use "Tweets.csv"  file which I have uploaded in this repository as well.

<h2>Data Description:</h2>

   - A sentiment analysis job about the problems of each major U.S. airline.
   - The Twitter data used in this project was scraped from February 2015. Contributors were asked to classify tweets into positive, negative, and neutral sentiments, and further categorize negative reasons such as "late flight" or "rude service"

<h2>Libraries Used</h2>

    - pandas: Data manipulation and analysis.
    - nltk: Natural Language Toolkit for text processing.
    - BeautifulSoup: HTML parsing for text data.
    - contractions: Library for expanding contractions in text.
    - numpy: Numerical computing library.
    - sklearn: Machine learning library for model building and evaluation.
    - matplotlib, seaborn: Visualization libraries for plotting result.

<h2> Data Preprocessing </h2>
    - Loading Data: The data is loaded from the provided CSV file using pandas.
    - Data Cleaning:
        HTML tags are removed from the text using BeautifulSoup.
        Contractions in the text are expanded using the contractions library.
        Numbers are removed from the text using regular expressions.
    - Tokenization: The text is tokenized into words using NLTK.
    - Stopword Removal: Stopwords (common words like "the," "is," etc.) are removed from the text.
    - Lemmatization: Words are lemmatized to their base form to reduce variation
    
<h2>Feature Engineering</h2>
    - The text data is vectorized using CountVectorizer and TF-IDF Vectorizer to convert it into numerical features suitable for machine learning models.
    - The feature space is limited to 5000 features to reduce processing time.

<h2>Model Building and Evaluation</h2>

    - Vectorize the text data using either CountVectorizer and TfidfVectorizer.
    - Build a classification model using techniques I use Random Forest.
    - The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.
    - Evaluate the model using cross-validation and confusion matrix.
    - Plot visualizations to understand model performance.
    - Confusion matrices and heatmaps are used for visualizing the model's predictions.

<h2>Results</h2>
    - The model achieved an average accuracy of approximately 75.32% using <b>CountVectorizer</b> and 76.53% using <b>TF-IDF Vectorizer.</b>
    - Confusion matrices show the distribution of predicted sentiment classes.

<h2>Summary:</h2>

- Use dataset which has tweets in text format and their sentiment type (positive, negative and neutral).
- The goal was to build a model for text-classification.
- Pre-processed the data using various techniques and libraries.
- The pre-precessed data is converted to numbers, so that I can feed the data in the model.
- After building the classification model, predicted the result for the test data.
- After that I saw that using the above techniques, our model performed good in perspective of how the text classifiaction models perform.
- One more way to increase accuracy is to use different variations of Pre-processing techniques. 


