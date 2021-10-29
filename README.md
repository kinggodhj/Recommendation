# Recommendation System

## Dataset

- Dividing the dataset into "train", "validation", "test" (User exlusive)

- Dividing validation and test set -> validation train / validation test

   validation train and validation test are item exclusive 
 
- data dim (batch, #item) 
  
- Input matrix consists of 0, 1 in implicit feed back (transforming the data into binary type using threshold) 

### Benchmark datasets

MovieLens-20M [link](https://grouplens.org/datasets/movielens/20m/)

MSD (Million Song Data) [link](http://millionsongdataset.com/)


## Evaluation

- Trian
  
   Input == output 
   
- Validation & Test

   Input =/= output
   
   Recommend item using the input item's information

### Metrics

NDCG k 
 

## Papers

RecVAE: a New Variational Autoencoder for Top-N Recommendations with Implicit Feedback

 -> Composite prior 

Enhancing VAEs for Collaborative Filtering: Flexible Priors & Gating Mechanisms
  
 -> RecVAE + gate 
 
 : Because of gate, training speed is slower than VAE model 
  
   Regarding to performance, it is slightly higher than VAE model's
 
 
