# Team-Brighter-2021-Fake-Reviews-Detection
Fake news has become a major problem in this modern world . The goal of fake news detection is to classify the real and fake news articles. In order to attract the readers, social media and news article writers publish the fake news. The internet has become a platform to get income. But with the popularisation of the Internet, it is challenging to develop fake news filters that can effectively eliminate unwanted news before they publish. The purpose of the work is to come up with a solution that can be utilised by users to detect and filter out sites containing fake and misleading information. We use simple and selected features of the data set which is used to identify whether the news article is fake or real. In this paper, propose a novel method for fake news detection using SGD classifier which achieves an accuracy of 94% with the test data sets.

What is TfidfVectorizer?

TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

SGD Algorithm: Gradient descent is an algorithm used to perform optimization and by far the most common way to optimize neural networks. Batch gradient descent performs unnecessary calculations for large datasets, as it recomputes gradients for related examples before each parameter update. SGD does away with this redundancy by performing one update at a time. Therefore SGD is much faster and can also be used to learn online. SGD performs frequent updates with a high deviation that cause the objective function to oscillate heavily.
