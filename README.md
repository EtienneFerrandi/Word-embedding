# Word-embedding

We use word2vec algorithm (unsupervised machine learning), with two different methods,  Continuous Bag Of Words (CBOW) and Skip-gram. The first model, CBOW, aims at predicting the target word, knowing the context. The second, Skip-Gram, aims at predicting the words of the context, knowing the target word.
Word embedding relies on a fundamental linguistic assumption: two different words appearing in similar contexts are related to each other semantically. This is what we called the distributional hypothesis. According to the famous article of Mikolov (2013), we use a convolutive neural network.

