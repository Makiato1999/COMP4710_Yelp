# Text Mining: Sentiment Analysis and Recommendation System on Yelp Reviews
Yelp is a platform that provides consumers to discover, connect and transact with local businesses, which allows consumers to make reviews, reservations, appointments, and purchases on businesses. In real life, other people's opinions are crucial in future decisions. Besides, in the commercial field, people's reviews can help merchants know customers' preferences. Online review platforms and merchants can get information from customers' reviews to make personalized recommendations for other customers, from which customers can also benefit. This project uses multiple text data mining methods to discover the potential information, analyze the text sentiment and construct a recommendation system. We used the Yelp review database to analyze the sentiment inside reviews and found patterns to provide personalized customer recommendations.
<br><br>
This is a COMP4710 group project completed by How Yun Ji, Xiaoran Xie, Runyu Fang, Zhijie Zheng. We implemented the K-mean clustering algorithm to cluster business locations, used natural language processing techniques to clean the data, vectorized the text of the review by word counts & TF-IDF, visualized the word frequency, found associate words in context by Word2Vec, searched the optimal hyper-parameters and classification model by k-fold cross validation, found the most suitable sentiment analysis classifier by comparing the results of logistic regression and support vector machine, extracted principal components of business by non-negative matrix factorization and retrieved similar business by k-mean clustering.


---

## How To Run
The program has been seperated into 3 stages. Note that at the end of the first stage, we randomly select a specific amount of data, so every different run will produce a different result.

### Prerequisites
- Jupyter Notebook
    - Jupyter notebook is required for running the code. 
- Yelp Datasets
    - The size of Yelp datasets is too large which exceed the GitHub maximum upload file size. So to be able to run the code, it is required to download the [datasets from Yelp](https://www.yelp.com/dataset).
    - In this program we only need business.json and review.json.
    - After you have downloaded the datasets, please put the file into the Datasets folder.
    
### Instructions
Below is the order of codes to be run.
- First Stage
  1. Data_Preprocessing.ipynb
  2. Filter_Reviews.ipynb

- Second Stage
  1. Process_Reviews.ipynb
  2. Analysis_Sentiment.ipynb
  
- Third Stage
  1. NMF_Model.ipynb
  2. Clustering_Topics.ipynb
  
---

## Authors and Acknowledgments
- Group members
  - [Xiaoran Xie](https://github.com/Makiato1999)
  - [Runyu Fang](https://github.com/Yorifong)
  - [Zhijie Zheng](https://github.com/ZhijieZheng-UM)
  - [How Yun Ji](https://github.com/yunji0387)

---

## Resources
- Yelp Datasets
  - https://www.yelp.com/dataset
