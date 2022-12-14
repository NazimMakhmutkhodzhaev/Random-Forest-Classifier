Random-Forest-Classifier

Here is presented the Random Forest Classifier implemented in python. Sklearn.ensemble library was used to import the RandomForestClassifier class and thus the objest of the class was created.

The initial model was only given 10 decision tree, which resulted in a total of 10 incorrect prediction. Once the model was fitted with more the decision trees the number of incorrect prediction grew less.

The most fitting number of decision trees for this models to predict the answers is around 200. Hence the n_estimator argument was given a final value of 200.
Anything more that 200 will result in over-fitting and will lead further incorrect prediction.
