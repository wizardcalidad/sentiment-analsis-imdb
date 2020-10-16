# sentiment-analsis-imdb
a sentiment analysis on a data set from imdb movie reviews using naive bayse algorithms of multinomial, bernoulli and complement to know which is more efficient type of naive bayse to deal with sentiment analysis or text classification.


# Setup
Before going through the steps make sure you have the following pre-installed

## Prerequisite
  1. Python 3.8+
  2. Virtualenv
  3. jupyterlab==2.2.8
  4. nltk
  
 Make sure to download/clone this repository and navigate to the folder in your terminal. 
  1. Create the virtual environment.
  2. Activate the environment and install dependies:
   
       pip install -r requirements.txt
 
 # Contents
 - Multinomial Naive Bayes (MultinomialNB)
    - With Count Vectorizer the metrics that were achieved in this model are as follows:
      - Minimum Accuracy : 46.67%
      - Maximum Accuracy : 67.57%
      - Mean Accuracy :    56.44%
      - Standard Deviation :0.0530
      
    - With TfidfVectorizer the metrics that were achieved in this model are as follows:
      - Minimum Accuracy :  49.33%
      - Maximum Accuracy :  60.00%
      - Mean Accuracy :     54.82%
      - Standard Deviation :0.0320
      
  - Bernoulli Naive Bayes (BernoulliNB)
    - With Count Vectorizer the metrics that were achieved in this model are as follows:
      - Minimum Accuracy : 66.67%
      - Maximum Accuracy : 81.33%
      - Mean Accuracy :    75.94%
      - Standard Deviation :0.0469
      
    - With TfidfVectorizer the metrics that were achieved in this model are as follows:
      - Minimum Accuracy : 66.67%
      - Maximum Accuracy : 81.33%
      - Mean Accuracy :    75.94%
      - Standard Deviation :0.0469
      
  - Complement Naive Bayes (ComplementNB)
    - With Count Vectorizer the metrics that were achieved in this model are as follows:
      - Minimum Accuracy :  68.00%
      - Maximum Accuracy :  81.33%
      - Mean Accuracy :     75.53%
      - Standard Deviation :0.0403
      
    - With TfidfVectorizer the metrics that were achieved in this model are as follows:
      - Minimum Accuracy :  68.00%
      - Maximum Accuracy :  85.33%
      - Mean Accuracy :     79.55%
      - Standard Deviation :0.0446
      
 # Summary
 With insights derived from the three models, we can always say the complement naive bayes algorithm is the best for this dataset while using TfidfVectorizer.
  
 # References
  - World Quant University
  - Machine Learning Mastery
  - towardsdatascience.com
  - Semicolon Machine Learning Community
  
                                                                                                                                                                 