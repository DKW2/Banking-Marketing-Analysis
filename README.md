# Banking-Marketing-Analysis

This project is my third and last practical application from UC Berkeley's MLAI bootcamp. The task is to analyze a dataset of marketing banking campaigns through telephone to classify whether a client would subscribe to a deposit term or not. The full work and report can be found on this notebook.

# Report
Starting With a dataset of 41188 entries, I first checked to see that the two classes are unbalanced with a split of around 90-10 (no, yes). I then proceeded to explore the data, taking note of categorical and numerical features as well as indentifying potential features to manipulate/remove. One feature that had to be removed was the "call duration" feature, since the feature can only be recorded during the call, not before.

Once I cleaned the data, I first created a baseline model to have a threshold for my models to beat. The model would always output "no", resulting in a baseline accuracy of around 88.9%. Once the baseline was established, I began training the classification models. For this project, I trained 4 different types of classification models: K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machines (SVC), and Decision Trees. For the first run, I trained all four models with their base settings, leading to these results:

![](images/baseModels.png)
