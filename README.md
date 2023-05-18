# NLP
Building a Random Forest model to detect the Spam text messages.
I go from messy, unstructured data set to concise predictions. 


### Steps:
It is important to examine the data first to see if any patterns can be recognized so that parsing operations can be optimized. we do that in the exploring data stage. then we follow the follwing steps:

1.	the first thing first, we tokenize our text. Meaning splitting the sentence to the words by taking care of white space or special characters

2.	now that we have a list of tokens/words with some non-important words like stop words (the, and, of,..) or stemming words (learn, learned and learning) that we need to remove them  

3.	then we convert the token to a format that a machine learning algorithm can actually ingest and use to build a model. This is a process called vectorising, and it's basically converting the text to a numeric representation of that text, where we can count the occurrences of each word in each text using a matrix with one row per text and one column per word.

4.	now that we have this numeric matrix, we can fit the actual machine learning model by feeding in the vectorized data along with the spam or ham labels. The model will then learn the relationships between the words and the labels in order to train a model to make predictions on text messages that it has never seen before and determine whether they are spam or not. 


5.  we do the Feature Engineering to find more new features/variables to use in the model to better filter spam messages

6.	we test out a number of candidate machine learning models before selecting which model performs best. Once we select the best model, we’ll evaluate that on a test set, to see how the model will perform on data that it's never seen or touched before. 

