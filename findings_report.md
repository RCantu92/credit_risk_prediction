# Unit 11 Homework: Machine Learning - Findings Report

## Resampling Report:

>	Which model had the best balanced-accuracy score?

The model with the best balanced-accuracy score is the SMOTE Oversampling model with a score of 65.16%. The next would be the Random Oversampling model with a balanced accuracy score of 64.92%. It is interesting to note the fact that both oversampling models had the best and second-best accuracy scores.

>	Which model had the best recall score?

Again, the SMOTE Oversampling model had the best recall score with 67%. The Random Oversampling model is second with a score of 65%.

>	Which had the best geometric mean score?

The Random Oversampling and SMOTE Oversampling model are tied for the best geometric mean score with 65%.

## Ensemble Learning Report:

>	Which model had the best balanced-accuracy score?

The EasyEnsemble model had the best balanced-accuracy score with 100%. This score is suspiciously high, but I have tried to reconfigure the code to output something more realistic to no avail.

>	Which had the best recall score?

EasyEnsemble with 100%. Suspiciously high.

>	Which had the best geometric mean score?

EasyEnsemble. See above.

>	What are the top three features?

The top three features are loan status-high risk, loan status-low risk, and total rec int. Their importances are 38.63%, 25.77%, and 4.82%, respectably.