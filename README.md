# Naive_bayes_ML_Assignment
### Data Preprocessing:
* Special characters were removed using regular expression.
* All the words were converted to lower case so as to not differentiate between words like The,THE,the.
* Stopwords were removed.
* Laplacian smoothening was used to avoid zero probability (Every word had at least one minimum occurrence in both positive and negative words)

### Results 
Without preprocessing the accuracy was around 69%.
After preprocessing Mean Accuracy:80.70%
Final Result: Accuracies: [77.0, 75.0, 85.0, 77.0, 86.0, 81.0, 84.0, 85.0, 76.0, 81.0]
F-Scores: [0.8, 0.7311827956989247, 0.8598130841121494, 0.7676767676767676, 0.8541666666666666, 0.8376068376068375, 0.8333333333333333, 0.8623853211009175, 0.7777777777777778, 0.8224299065420562]
Mean Accuracy: 80.700% Accuracy stddev: 4.191 Mean F-Score: 0.815 F-score stddev: 0.044
Accuracy=0.807 ± 0.0491
F-score=0.815 ± 0.044
