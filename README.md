# Fake_News_Detection
In this we shall be detecting fake news with Python and Machine Learning

### What is Fake News?
Fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. This is often done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, and may end up being viralized by algorithms, and users may end up in a filter bubble.

### What is TfidfVectorizer?
#### TF (Term Frequency)
The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

#### IDF (Inverse Document Frequency)
Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

### What is PassiveAggressiveClassifier?
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.

### Below are the project steps:
* To build a model to accurately classify a piece of news as REAL or FAKE.
* Using sklearn, we build a TfidfVectorizer on our dataset.
* Then, we initialize a PassiveAggressive Classifier and fit the model.
* In the end, the accuracy score and the confusion matrix tell us how well our model fares.

The data-set for this project can be downloaded from the below mentioned link, 

[Data-Set](https://drive.google.com/file/d/1er9NJTLUA3qnRuyhfzuN0XUsoIC4a-_q/view)

[Code](https://github.com/alinauman/Fake_News_Detection/blob/main/Detecting%20Fake%20News%20with%20Python%20and%20Machine%20Learning.ipynb)

We can see that we are seeing an accuracy of around 92.42%. Along with that, we have 589 true positives, 587 true negatives, 42 false positives, and 49 false negatives.
