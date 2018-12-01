### GluonRank: Your Choice of Deep Learning for Ranking

GluonRank is a toolkit that enables easy implementation of collaborative filtering models using neural networks, to help your prototyping of state of the art ranking systems.


## ToDo

- [ ] Training loss does not go to zero. Understand why. Start by taking movielense data from spotlight, comparing sampling method etc.
- [ ] Create hosted docs
- [ ] Create python package

## Ideas

1. Positive and negative items could be in the same tensor, on different axis
2. Can construct a single lookup table for all categorical variables. Vocab_size = np.unique(user_embed_features)
    - Need to index cols to ensure there is no collision between variables
3. The dataset could return a positive with some probability, otherwise returning a negative randomly sampled from a sparse matrix
4. Loss functions should be custom and take both pos_pred and neg_pred
5. 
    
```python

```


