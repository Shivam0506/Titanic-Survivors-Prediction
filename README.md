# Titanic-Survivors-Prediction

You are tasked with predicting the survival or passangers on the titanic based on various features such as age,sex,class,etc.Using the titanic dataset you will implement logistic regression to create a predictive model and evaluate its performance

Survival: Indicates whether the passenger survived (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex: Gender of the passenger
Age: Age of the passenger in years
SibSp: Number of siblings or spouses aboard the Titanic
Parch: Number of parents or children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of Embarkation:in which port the passanger has boarded the ship.C = Cherbourg, Q = Queenstown, S = Southampton

1.Accuracy:
Training Accuracy (81%): Indicates that the model performs well on the training data.
Testing Accuracy (78.21%): Slightly lower accuracy on the testing set may indicate some overfitting, where the model performs well on training data but less so on unseen data.

2.Precision (0.845): High precision indicates that when the model predicts survival, it is correct about 84.5% of the time. This suggests the model is good at minimizing false positives.

3.Recall (0.620): Lower recall suggests that the model correctly identifies 62% of actual survivors. This means there are a considerable number of false negatives (missed survivors).

4.F1 Score (0.715): The F1 Score balances precision and recall. A score of 0.715 indicates a reasonable balance but leaves room for improvement
