<h1>Sentiment Analysis </h1>
    This project focuses on sentiment analysis regarding the problems of major U.S. airlines using Twitter data. The dataset was scraped in February 2015 and includes tweets categorized as positive, negative, or neutral, along with categorization of negative reasons.

<h1>Dataset:</h1>
    The project is from a dataset from Kaggle.
    Link to the Kaggle project site:https://www.kaggle.com/crowdflower/twitter-airline-sentiment
    The dataset has to be downloaded from the above Kagglewebsite.

<h2>Data Description:</h2>

    A sentiment analysis job about the problems of each major U.S. airline.
    The Twitter data used in this project was scraped from February 2015. Contributors were asked to classify tweets into positive, negative, and neutral sentiments, and further categorize negative reasons such as "late flight" or "rude service"

<h2> Loading and Preprocessing Data </h2>
        Load the dataset into a Pandas DataFrame  using pandas read_csv() function.        
        Perform data preprocessing steps such as removing HTML tags, replacing contractions, removing numbers, tokenization, removing stopwords, and lemmatization.

<h2>Model Building and Evaluation</h2>

    Vectorize the text data using either CountVectorizer or TfidfVectorizer.
    Build a classification model using techniques I use Random Forest.
    Evaluate the model using cross-validation and confusion matrix.
    Plot visualizations to understand model performance.

<h2>Summary:</h2>

- Use dataset which has tweets in text format and their sentiment type (positive, negative and neutral).
- The goal was to build a model for text-classification.
- Pre-processed the data using variuos techniques and libraries.
- The pre-precessed data is converted to numbers, so that I can feed the data in the model.
- After building the classification model, predicted the result for the test data.
- After that I saw that using the above techniques, our model performed good in perspective of how the text classifiaction models perform.
- One more way to increase accuracy is to use different variations of Pre-processing techniques. 


