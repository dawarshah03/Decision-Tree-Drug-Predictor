# Drug Prediction Using Decision Tree

So in this simple machine learning project, I used a CSV file drug200.csv to predict which drug should be given to a patient based on some features like age, sex, blood pressure, cholesterol, and Na_to_K.

I did some basic preprocessing by encoding the text columns like Sex, BP, and Cholesterol using LabelEncoder, and dropped the original ones.

Then I split the data using train_test_split (80% for training and 20% for testing).

After that, I trained a DecisionTreeClassifier on it and made predictions.
Main thing was to try out how decision trees work and how to prepare the data before training.
