# cyberbullying
Brief Background:
 
  Words, once a means of flattery and praise between individuals, have transformed into tools for attack with the rise of social media, particularly among Gen Z. These platforms have magnified every word and action, subjecting them to judgment by the masses. Consequently, prejudiced comments have overwhelmed popular social media platforms like Instagram and Twitter. As one of the largest platforms, Twitter alone contains countless tweets targeting various topics and individuals. Determining whether these tweets classify as cyberbullying or not can be challenging. Are there any patterns or models available to identify cyberbullying?
  
  In the project, I will use the cyberbullying dataset from Kaggle to analyze the sentiment scores and patterns (words) associated with each cyberbullying type. Through NLP classification, specifically Multi Classification and Binary Classification to determine the types of cyberbullying and if the tweet is an act of cyberbullying. 

Goals of the Project:

1. Identify the distribution of the cyberbullying types 
2. Use NLP preprocessing techniques preprocess the tweets and create data visualizations 
3. Determine the sentiment distribution of the tweets and the patterns associated with each cyberbullying types 
4. Create Multi Classification models to classified the tweets into the 6 cyberbullying types 
5. Create Binary Classification models to classified the tweets into not cyberbullying and cyberbullying 
6. Assess the accuracy of the models using accuracy metrics


Resources of data:
1. Cyberbullying Classification Dataset From Kaggle:

  https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification

This repository contains the following files
1. Cyberbullying -  CSV
2. Cyberbullying  - IPYNB (Data Preprocessing, Data Exploration, Multi Classification, Binary Classification)
3. Model Evaluation of the IPYNB

Some conclusions: 

For the "not_cyberbullying" category, the words mostly have a neutral sentiment but do contain words that are also present in other types of cyberbullying, such as "school" and "bully." In the "gender" type of cyberbullying, the words used hint at disrespect and harassment, including terms like "r*pe," "g*y," "woman," "b*tch," and "sexists." Similarly, for the "religion" type of cyberbullying, the words include terms like "muslim," "idiot," "christian," "terrorists," and "islamic." These words are related to negative stereotypes and events involving religious communities. The "age" type of cyberbullying includes words like "school," "bully," "high," "kid," and "girl." These words appear most frequently as younger individuals tend to exhibit more impulsive and rant-like behavior. These keywords are often associated with younger age groups. In the "ethnicity" type of cyberbullying, words like "nigg**," "black," "f*ck,”, “white," and "obama " are included. These words represent racial conflicts and slurs, as well as famous figures associated with certain races. Lastly, the "other_cyberbullying" category contains words from various other types, including "bully," "f*ck," "people," and "idiot." This category encompasses a broad range of discriminatory words, with many related to appearance/online presences

Among the multi-classification models, the Gradient Boosting model perform the best with a macro average of 0.83, followed by Random Forest (0.82), and lastly Naive Bayes (0.72). For the Binary Classification models, based on multiple metrics such as sensitivity, specificity, and accuracy the Logistic Regression model perform better than the SVM model 
