# Final Year Project
## Interpretable Vector Language Models

### Abstract
Natural Language Processing (NLP) is a branch of computer science that focuses
on the development of algorithms for understanding, interpreting, and generating
human language texts. A crucial technique in NLP is word embedding, where models
such as Word2Vec and GloVe assign vectors to words in a vocabulary such that
the Euclidean space structure (norms and angles of word vectors) aligns with the
semantic structure of the training corpus. Despite their effectiveness, the individual
entries of word embedding models are difficult to interpret due to the simultaneous
rotation of all pre-trained word vectors preserves norms and angles while mixing
up individual entries. In this study, we proposed a novel approach for generating
word embeddings with interpretable entries. To achieve it, we introduced a metric to
quantify the interpretability of a word embedding model. Additionally, we connected
the interpretability of a word embedding model to a specific loss function defined on
the Lie group SO(d). We then compared three loss functions, namely, the Varimax
loss function inspired by factor analysis, the l1-norm, and a combination of the two.
Our results showed that the Varimax loss function yielded word embeddings with
the highest interpretability among the three methods, as it maximizes the sum of
the variances of squared entries, enabling successful interpretation of some columns
in the resulting word embedding matrices. This study offers insights into generating
interpretable word embeddings while preserving semantic structure.
