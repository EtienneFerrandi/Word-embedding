# Word-embedding

We use word2vec algorithm (unsupervised machine learning), with Continuous Bag Of Words (CBOW) and skip-gram methods. CBOW aims at predicting the target word, knowing the context. Skip-gram aims at predicting the context, knowing the word.
Word embedding relies on a fundamental linguistic assumption: two different words appearing in similar contexts are related to each other semantically. This is what we called the distributional hypothesis. According to the famous article of Mikolov (2013), we use a convolutive neural network in order to detect them.

