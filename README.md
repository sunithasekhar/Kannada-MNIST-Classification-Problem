## Kannada MNSIT Classification Problem ##
This is an extension of classic MNSIT classification problem. The Dataset can be downloaded from the link : https://www.kaggle.com/datasets/higgstachyon/kannada-mnist. The dataset includes Kannada( a language in south-western India) numerals. This is a 10-Class classification problem.

### Problem Solution Outline ###
 1. *There are 60000 images for training and 10000 for testing. Each image is of size 28X28.*
 2. *Perform **PCA** to 10 components*
 3. *Apply the following **ML** models*
    - Decision Trees
    - Random Forest
    - Naive Bayes Model
    - KNN classifier
    - SVM
4. #### For each of the above models, the following matrices are produced ####
   - Precision, Recall, F!-score
   - Confusion matrix
   - RoC AUC curve   
5. #### The experiment is repeated for different component size : 15,20,25,30 ####
