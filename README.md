# Bias-of-Classifiers
Jupyter notebook on the how majority bias can effect different classifiers and methods of reducing bias.

### The Effect of Bias
To evaluate the possible bias toward the majority class I will test k-NN, Decision Trees, Logistic Regression and lastly Gradient Boosting classification algorithms. For each of them I will use hold-out testing and cross-validation to evalute the performance of the classifiers, and especially look to see how it classifies our minority set.

### Strategies to Rectify Bias
There are 2 main types of techniques for handling imbalanced datasets, sampling and cost-sensitity. For sampling I will be using both SMOTE upsampling, and downsampling. Lastly I will evaluate the effect of up-weighting and down-weighting for a cost-senstivite method to reduce bias.
