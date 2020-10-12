# Movie-Review-with-Naive-Bayes-Algorithms-and-Cross-validation

  Machine learning project on Sentiment Analysis movie review using Naive Bayes Algorithms, such as:
  MultinomialNB, ComplementNB, BernoulliNB. Using an imdb dataset to carry out the exercise and looking 
  out for which one of the algorithms is performs most efficiently in the Sentiment Analysis Movie Review.
  
# Set Up

  Before the commencement of the exercise the following utilities were pre-installed:
  
  -Prerequisite:
    
    1. Python 3.8+
    2. Virtualenv
    3. jupyterlab==2.2.8
    4. nltk
Make sure to download/clone this repository and navigate to the folder in your terminal.

    1. Create the virtual environment.

    2. Activate the environment and install dependies:

       pip install -r requirements.txt
   
# Content

  # Multinomial Naive Bayes (MultinomialNB)

   - With Count Vectorizer the metrics that were obtained in this model are as follows:
   
    . Maximum Accuracy : 67.57%
    . Minimum Accuracy : 46.67%
    . Mean Accuracy : 56.44%
    . Standard Deviation :0.0530
    . With TfidfVectorizer the metrics that were obtained in this model are as follows:

    . Minimum Accuracy : 
    . Maximum Accuracy : 
    . Mean Accuracy : 
    . Standard Deviation :
    
# Complement Naive Bayes (ComplementNB)

  - With Count Vectorizer the metrics that were obtained in this model are as follows:
  
    - Minimum Accuracy : 68.92%
    - Maximum Accuracy : 50.67%
    - Mean Accuracy : 57.38%
    - Standard Deviation :0.0559
    
# With TfidfVectorizer the metrics that were obtained in this model are as follows:

    - Minimum Accuracy :
    - Maximum Accuracy : 
    - Mean Accuracy : 
    -Standard Deviation :
    
# Bernoulli Naive Bayes (BernoulliNB)

 - With Count Vectorizer the metrics that were obtained in this model are as follows:

    - Maximum Accuracy:   68.00%
    - Minimum Accuracy:   42.67%
    - Mean Accuracy:   57.09%
    - Standard Deviation: 0.0745
 
# With TfidfVectorizer the metrics that were obtained in this model are as follows:

    - Minimum Accuracy : 
    - Maximum Accuracy : 
    - Mean Accuracy : 
    - Standard Deviation : 
    
 # Summary
 
  - From the above result it can be easily seen that Complement algorithm shows the result of 
    best performance. And we go for it.
 
 # Referrences
 
    - stackabuse.com/python-nlp-for-sentiment-analysis-with-scikit-learn/
    - scikit-learn.org/stable/auto_example/
    - semicolon-tech-github
