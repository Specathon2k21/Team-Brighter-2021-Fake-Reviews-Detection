# Team-Brighter-2021-Fake-Reviews-Detection
Fake news has become a major problem in this modern world . The goal of fake news detection is to classify the real and fake news articles. In order to attract the readers, social media and news article writers publish the fake news. The internet has become a platform to get income. But with the popularisation of the Internet, it is challenging to develop fake news filters that can effectively eliminate unwanted news before they publish. The purpose of the work is to come up with a solution that can be utilised by users to detect and filter out sites containing fake and misleading information. We use simple and selected features of the data set which is used to identify whether the news article is fake or real. In this paper, propose a novel method for fake news detection using SGD classifier which achieves an accuracy of 94% with the test data sets.

# What is TfidfVectorizer?

TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

# SGD Algorithm:
Gradient descent is an algorithm used to perform optimization and by far the most common way to optimize neural networks. Batch gradient descent performs unnecessary calculations for large datasets, as it recomputes gradients for related examples before each parameter update. SGD does away with this redundancy by performing one update at a time. Therefore SGD is much faster and can also be used to learn online. SGD performs frequent updates with a high deviation that cause the objective function to oscillate heavily.

# IMPLEMENTATION
- The vectorisation concept which converts the text data into the numerical data for input of algorithm. 
- The input doesn’t contain any punctuations and stop words in the data set which gives the more accuracy.
- The fundamental point of stochastic gradient descent  is to create a model which predicts class labels of information occurrences in the testing set which are given only the features. 
- Stochastic gradient descent algorithm is a splendid solution for the little sample size issue, by developing an isolating the hyperplane to finish the classification.

# RESULTS
The fake news detection project has been completed using Term Frequency–Inverse Document Frequency (TF–IDF), Count Vectoriser(CV) and SGD classifier which achieves an accuracy of 94% with the test datasets.

# FUTURE SCOPE
- To build a software model which can differentiate between fake and real news.
- To develop an android app which will trigger on a copy of the text and when user will click on application popup the data or copied text will be sent to the server to check and as per the authenticity will be displayed to the user. 
- To review current industry practices and researches regarding stopping the spread of fake news.
- It is difficult for illiterates to use the existing solution so we need to develop an inbuilt software for every laptop , phone to detect the fake news. 
The result of this project will be valuable to the researchers as well as to social media giants in developing better practice and tools for detecting fake news.

# CONCLUSION
- Using stochastic gradient descent classifier, the fake news detection which can effectively identify the fake news from its contents. The fake news can be identified by the user and genuine content can be retained by the user.
- The proposed classifier achieves 94 % accuracy while classifying the series of datasets. 
- It is crucial that we have some system for detecting fake news, or at the very least, an awareness that not everything we read on social media may be true, so we always need to be thinking critically.
- This way we can help people to take more correct decisions and they will not be fooled into thinking what others want to manipulate them into believing.
