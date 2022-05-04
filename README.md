# Rectifing the Bias of Classifiers
Jupyter notebook on the how majority bias can effect different classifiers and methods of reducing bias.
Included are two notebooks, the first investiagtes the effect of bias, and different strategeis to rectify the bias. The second notebook looks into rectify the bias with pipeline strategies, and then into feature selection.

## Bias of Classifiers
### The Effect of Bias
To evaluate the possible bias toward the majority class I will test k-NN, Decision Trees, Logistic Regression and lastly Gradient Boosting classification algorithms. For each of them I will use hold-out testing and cross-validation to evalute the performance of the classifiers, and especially look to see how it classifies our minority set.

### Strategies to Rectify Bias
There are 2 main types of techniques for handling imbalanced datasets, sampling and cost-sensitity. For sampling I will be using both SMOTE upsampling, and downsampling. Lastly I will evaluate the effect of up-weighting and down-weighting for a cost-senstivite method to reduce bias.


## Rectifying Bias And Feature Selection

### Part 1: Pipelines: Rectifying Bias - Cross Validation
To reduce bias I will be using Pipeline with Cross Validation, and SMOTE upsampling. To compare its effectivness I will compare the it to hold-out testing (with and without SMOTE).

### Part 2: Feature Selection
To explore the impact of feature selection I will be using Backwards Sequential Elimination.
