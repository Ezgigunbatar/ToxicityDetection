# ToxicityDetection
Toxicity detection on imbalanced social media data

In this study, user comments on an online platform "Civil Comment" were used as data form Kaggle: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/data.
I focused on 2 main topics of toxicity detection: Class imbalance problem and detecting toxic comments.

To ride of class imbalance problem two sampling methods were used:  Random undersampling and oversampling with SMOTE. After this step, two machine learning (ML) models (Logistic regression and Stochastic gradient descent classifier) were applied to the original and resampled data to detect toxic comments. Since I worked with text data, in order to make the data usable for the learning models, it needs to be converted into numerical vectors.  Term Frequency-Inverse Document Frequency (TF-IDF) one of the vectorization techniques was used to extract these vectors in the study, so that they can be used by ML models.
In the end, performance evaluations and comparisons were made and reported.
