# FDA_hw3

## Data Set - [S&P 500](https://www.sharecast.com/index/SP_500/prices/download)
* Training set
  * 02-Jan-2009 to 29-Dec-2017
* Test set
  * 02-Jan-2018 to 31-Dec-2018
 
## Discussion
* How did you preprocess this dataset ?
  * Detail in python files' comments.
* Which classifier reaches the highest classification accuracy in this dataset ?
  * Logistic test accuracy: 50%
  * **SVM accuracy: 51.59%** (highest)
  * Neural Network accuracy: 49%
* Why ?
  * Although the result didn't seem so much different, but I guess that SVM can get a good balance between empirical risk 
  and generalization risk, that why it will have a better accurracy.
* Can this result remain if the dataset is different ?
  * No, different dataset will affect the training performace. Thus it will have a different training result.
* How did you improve your classifiers ?
  * Tuning hyperparameter, droping useless columns, changing columns into more useful information(Split Date string), one-hot encoding
