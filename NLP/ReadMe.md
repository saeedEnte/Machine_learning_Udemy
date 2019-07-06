In this project we worked on the dataset called "yelp" driven from kaggel.
We did some exploratory data analysis, histograms, and visualizations and also tried to see some correlations between the features of the dataset. For the classification task we just worked with the data with 1 or 5 stars for their review. 
We tried to predict the stars of the reviews. Before that we did a data pre-processing step which was vectorizing the text using `CountVectorizer`
After spliting the data into train and test, we tried to classify the data using the nive-bayes with the method (`MultinomialNB`). Thereafter, we did an evaluation.
For the last part of the project, we created a pipline which undertakes the pre-process test and also did the classification task. We created a bag of words and also extract the tf-idf features. Finally came the classification process in the defined pipline. 
Then we made use of the defined pipline. We splited the data into the train and test data (raw data). Then fit the pipline into the train and applied it in the test data. After the prediction we did an evaluation for the process.
