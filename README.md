# Credit Card Dataset Models
Attempting different models on the "Default of Credit Card Clients Dataset" from kaggle:
- https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset

## Logistic Regression
Baseline Model: 
- train_accuracy: 0.7775555555555556
- test_accuracy: 0.7825333333333333
- train_f1: 0.0003994407829039345
- test_f1: 0.0012247397428046538
- train_precision: 0.3333333333333333
- test_precision: 1.0
- train_recall: 0.00019984012789768185
- test_recall: 0.0006127450980392157

Iterative Modeling Process:
- cleaned data
- created dummy variables
- min-max transformed variables
- log-transformed variables
- applied SMOTE to address class imbalance

Final Model:
- train_accuracy: 0.7019890260631001
- test_accuracy: 0.7770666666666667
- train_f1: 0.6576943277310925
- test_f1: 0.5292792792792792
- train_precision: 0.7725169648365207
- test_precision: 0.4895833333333333
- train_recall: 0.5725880201188843
- test_recall: 0.5759803921568627

## K Nearest Neightbors
Baseline Model: 
- train_accuracy: 0.8119111111111111
- test_accuracy: 0.7518666666666667
- train_f1: 0.4337704040674338
- test_f1: 0.23194387123400742
- train_precision: 0.6562753036437247
- test_precision: 0.3552465233881163
- train_recall: 0.3239408473221423
- test_recall: 0.1721813725490196

Iterative Modeling Process:
- cleaned data
- created dummy variables
- min-max transformed variables
- log-transformed variables
- applied SMOTE to address class imbalance

Final Model:
- train_accuracy: 0.8606824417009602
- test_accuracy: 0.6646666666666666
- train_f1: 0.8717881282381718
- test_f1: 0.434958436306448
- train_precision: 0.8074243679056852
- test_precision: 0.34338417878680383
- train_recall: 0.9473022405121171
- test_recall: 0.5931372549019608
