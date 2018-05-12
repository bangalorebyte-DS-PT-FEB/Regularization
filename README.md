# Regularization

The telecom dataset is also very interesting as the aim is to try and predict wheter a customer will leave a telecom operator based on cetain customer features.


- Process the dataset (manage categorial variables, consider min_max processing)
- Visualize the data (Aka, ask you data questions, what was the distribution of customer service calls for individuals who left the service? Is this a sign of an important feature)
- If at thet outset (pre-modelling) you feel some features are irrelevant, drop them. Best to keep them all for the first run however.
- Split your test and train.
- When applying your model take advantage of cross_val_score from sklearn.
- From a modelling POV, the main purpose here is to compare the (best) performances of LR, LDA/QDA, SVM and see if our theoretical justifications hold.
