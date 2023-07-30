# deep-learning-challenge
Siyuan Zhu - bootcamp -challenge 21

Overview:

This analysis aims to find and optimise the best possible Neural Network model with over 75% accuracy that can be used to predict whether applicants will be successful if funded by Alphabet Soup.

Result:

•	Optimisation 1: 
268/268 - 1s - loss: 0.5554 - accuracy: 0.7252 - 501ms/epoch - 2ms/step
Loss: 0.5554278492927551, Accuracy: 0.7252478003501892


•	Optimisation 2:
268/268 - 0s - loss: 0.5549 - accuracy: 0.7250 - 396ms/epoch - 1ms/step
Loss: 0.554854691028595, Accuracy: 0.7250145673751831


•	Optimisation 3:
268/268 - 0s - loss: 0.5580 - accuracy: 0.7249 - 455ms/epoch - 2ms/step
Loss: 0.5580396056175232, Accuracy: 0.7248979806900024


•	Optimisation 4:
268/268 - 0s - loss: 0.5551 - accuracy: 0.7254 - 406ms/epoch - 2ms/step
Loss: 0.555082380771637, Accuracy: 0.7253644466400146


Summary: 

In these four attempts to optimise the best possible model, it could not achieve the target accuracy of over 75%, but could be only at around 72.5%. So, some alternative datasets should be considered to see if they can better predict whether applicants will be successful, for example, we can include the feature of ‘’NAME’’ or “EIN” for optimising Neural Network Model.  

