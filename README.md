# Recommendation System

## Dataset

- Dividing the dataset into "train", "validation", "test" (User exlusive)

- Dividing validation and test set -> validation train / validation test

   validation train and validation test are item exclusive 
 
- data dim (batch, #item) 
  
- Input matrix consists of 0, 1 in implicit feed back (transforming the data into binary type using threshold) 

## Evaluation

- Trian
  
   Input == output 
   
- Validation & Test

   Input =/= output
   
   Recommend item using the input item's information

 

## Papers

RecVAE: a New Variational Autoencoder for Top-N Recommendations with Implicit Feedback

 -> Composite prior 
