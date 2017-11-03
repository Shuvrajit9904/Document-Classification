# Document-Classification
Using tf-idf and neural network classified news articles

Given a set of news articles and their category this code classifies the article into appropriate category
The data used here is the MUC3 terrorism dataset
the code reads Files from two Different Folder:
developset/texts, which contains the documents
developset/answers, which contains the labels
Answers are template based, which contains other information such as:
ID, INCIDENT, WEAPON, PERP INDIV, PERP ORG, TARGET, VICTIM
We Only need The value of Incident, which could any on the five below:
ATTACK, BOMBING, ARSON, KIDNAPPING, ROBBERY
We have used tf-idf vector to train the neural network.
Other classification methods like Naivebayes, k-nearest neighbours, K-means etc has also been tested
But Neural Network was producing highest accuracy in test set
