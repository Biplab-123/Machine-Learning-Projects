# Machine-Learning-Projects
I have made a SMS spam classifier.
The data was taken from the Kaggle itself.
While performing the EDA I observed the data was imbalance as the Ham messages count was much than spam messages count. 
Using NLP methos like Lower Caseimg, Tokenization, Remove Special Character, Remove Stop words and puntuations,stemming tto process the data. 
As it was a text classification and spam filtering so I have choose Naive Bayes Algorithm and it was best performing one over the other classification models(I have compared them all).
To Improve the performance I have change the max_feature hyperparameter of the TF-IDF vectorizer to 3000 and get the best accuracy and precision.
Thanks a ton to Nitish sir from campusx for the tutorial I have made the whole project from the Machine Learning Playlist from his Youtube channel.
