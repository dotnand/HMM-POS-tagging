# HMM-POS-tagging

1. Read the Womens Clothing E-Commerce Reviews.csv file and set it as a Dataframe called clothing_reviews. Check the head, info, and describe methods on the Dataframe

2. Remove punctuations and stopwords from the text in ‘text’ column

3. Create two objects X and y. X will be the ' Review Text ' column of clothing_reviews Dataframe and y will be the 'Rating' column. Create a CountVectorizer object and split the data into training and testing sets. Train a MultinomialNB model and Display the confusion Matrix

4. Display the HMM POS tagging on the first 4 rows of ‘Review Text’ 

 5 .Parse the first 4 rows of ‘Review Text’ using Viterbi Parser [Use toy_pcfg1 and toy_pcfg2 to get the probabilistic context free grammars; use the PCFG suitable for each sentence] 
