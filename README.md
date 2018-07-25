# Topic-Modeling-LDA
Latent Dirichlet Allocation (LDA) is used to discover topics that are present in a corpus


We will perform the following steps:
```
Tokenization: Split the text into sentences and the sentences into words. Lowercase the words and remove punctuation.
Words that have fewer than 3 characters are removed.
All stopwords are removed.
Words are lemmatized — words in third person are changed to first person and verbs in past and future tenses are changed into present.
Words are stemmed — words are reduced to their root form.
```

Created tf-idf model object using models,
Created bag of words model object,
For each document we create a dictionary reporting how many words and how many times those words appear using doc2bow
