Day 2 Observations:

- Learning rate 0.1 works well
- 1.0 diverges
- Cost function is convex (bowl-shaped)
- Gradient descent follows slope downhill

Day 3 Observations:

- Vectorization is much faster than loops
- Normal equation gives exact solution
- Gradient descent is iterative
- Normal equation doesn't scale to large data

Day 4 Observations:

- High model complexity is not always better.
- More complexity usually leads to  higher  variance and lesser the complexity more the 
bias.
- Regularization prevents overfitting.
- A good balance of model complexity and generalization erros is needed.

Day 5 Observations:

- Train error is always lower than test error
- Validation helps choose best model
- Overfitting detected using validation error
- Test set must not be used during training

Day 6 Observations:

- Cross validation gives stable estimates
- Uses full dataset efficiently
- Better than single train/test split
- Helps reliable model selection

Day 7 Observations:

- Review of all the concepts for the week.
- mini project on model selection using 5 fold cross validation.

Day 8 Observations:

- Logistic regression outputs probabilities
- Sigmoid squashes values to (0,1)
- Cross-entropy works better than MSE
- Decision boundary is linear

Day 9 Observations:

- Accuracy is not reliable for imbalanced data
- Precision focuses on false positives
- Recall focuses on false negatives
- F1 balances both

Day 10 Observations:

- Softmax outputs probabilities across classes
- One-hot encoding is required
- Cross-entropy works well for classification
- Softmax generalizes sigmoid

Day 11 Observations:

- ROC shows performance across thresholds
- AUC measures ranking quality
- Threshold selection is important
- ROC is useful for model comparison

Day 12 Observations:

- Scaling improves gradient descent speed
- Standardization is widely used
- Must fit scaler on training data only
- Scaling doesn't change model expressiveness
