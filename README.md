# Movie-Recommendations-using-Collaborative-Filtering

## Embedding matrix size 30
![curve1](embedding30.png) 
## Embedding matrix size 50
![curve2](embedding50.png) 
## Embedding matrix size 64
![curve3](embedding64.png)

**My work includes movie recommendations using collaborative filtering which is the most accurate way to recommend things. I have experimented with the size of embedding layer , batch_size and learning rate much and came to the final conclusion that particularly for this dataset the embedding layer of 30 was best in the sizes of 30,50 and 64 . Also the mean square error was better when kept layer size small. This might be due to the fact that the data might not be that complex to have feature extraction of upto 50 or 64. Extracting features upto this limit might have led the model to memorize and thus overfitting the data. The best mean square error achieves was of 0.8254.**
