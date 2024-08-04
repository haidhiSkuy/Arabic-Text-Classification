# Arabic Text Classification

In this project, I did some experiments with several vectorization methods such as TF-IDF, CountVectorized, and word2vec. The final result is that word2vec is not good enough. Decision tree also isn't good enough for text classification task, due to its disadvantages *curse of dimensionality*.

For text preprocessing, the overall process is the same with another language: stop word removal, stemming, and removing punctuation. Text preprocessing won't guarantee your model will perform better. It depends on the task


The datasets I used:
- SANAD : Single-label Arabic News Articles Dataset
- HARD : Hotel reviews in the Arabic language
- OCLAR : Opinion Corpus for Lebanese Arabic Reviews

