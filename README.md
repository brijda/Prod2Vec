We find neural embeddings for all items using user purchase sequences. (Similar to word2vec on sentences) (prod2vec.py) We recommend the items to the users which are more similar to their previous purchased items. The similarity is calculated using vector representation of items.
We enhanced the embeddings by adding item content information. We used these embeddings for recommendation. (prod2vec_enhanced.py)
