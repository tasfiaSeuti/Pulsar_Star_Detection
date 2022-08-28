# Pulsar_Star_Detection

### Definition of the problem
In this project, the idea is to predict if a star is a pulsar star or not. The 
result of the models will be binary: 1 if the star is a pulsar star and 0 otherwise. Thus,
I implemented classification models to answer this problem

### Description

Pulsars are a rare type of Neutron star that produce radio emission detectable here on Earth.
They are of considerable scientific interest as probes of space-time, the inter-stellar medium, 
and states of matter. Machine learning tools are now being used to automatically label pulsar candidates to facilitate rapid analysis. 
Classification systems in particular are being widely adopted, 
which treat the candidate data sets as binary classification problems.

### Choice of the machine learning models and the metrics to evaluate it

In this part, I implement different machine learning models that deal with classification problems and define measures to evaluate their performance.
For the machine learning models, I used the decision tree algorithm, the logistic regression algorithm, the random forest algorithm and 
the K-Nearest Neighbors algorithm. I used time, precision, recall, weighted f1 score and AUC score to evaluate the models.

### Performance Measure
I calculated a final measure which is the AUC curve. The AUC — ROC curve is a performance measure for classification problems at different thresholds.
ROC is a probability curve and AUC is the degree or measure of separability. It indicates how well the model is able to distinguish between classes. 
The higher the AUC, the better the model is able to predict that 0s are 0s and 1s are 1s.

### Result Analysis
Depending on the problem, the metrics don’t have the same weight on our results (in pictures). 
The AUC score is the most important metric in the model as predicting a star as a non super star and making a mistake is what 
we want to avoid. Thus the logistics regression seems to be the most efficient model.(shown in pictures)
![Screenshot 2022-08-28 at 11 17 12 AM](https://user-images.githubusercontent.com/31209824/187090221-e0c63aa0-b414-4f3e-96d7-82fc6230e50a.png)
![Screenshot 2022-08-29 at 12 46 58 AM](https://user-images.githubusercontent.com/31209824/187090222-5fa16ca1-eed2-440d-acf7-7b61c5d79bd5.png)

![Screenshot 2022-08-29 at 12 58 01 AM](https://user-images.githubusercontent.com/31209824/187090225-0da4fc0e-7a6e-4404-b822-5b49a5b4b3b0.png)
![Screenshot 2022-08-29 at 12 57 53 AM](https://user-images.githubusercontent.com/31209824/187090227-1eb30d27-a7cd-4832-9359-354d18b32c17.png)
![Screenshot 2022-08-29 at 12 57 42 AM](https://user-images.githubusercontent.com/31209824/187090231-32ea6f90-758b-4698-87eb-819cd87ad46b.png)
![Screenshot 2022-08-29 at 12 57 35 AM](https://user-images.githubusercontent.com/31209824/187090233-ad9882e3-00a5-4ac0-b195-f6a0b9aa7ee8.png)

### Other Screenshots
![Screenshot 2022-08-28 at 11 15 35 AM](https://user-images.githubusercontent.com/31209824/187090274-c6353dbe-8bf9-43bf-ac21-a14d141ed85f.png)

![Screenshot 2022-08-28 at 11 16 12 AM](https://user-images.githubusercontent.com/31209824/187090278-35585280-a052-42b6-a818-0644789e65d4.png)
![Screenshot 2022-08-28 at 11 16 23 AM](https://user-images.githubusercontent.com/31209824/187090280-33b89bbd-5da7-4993-b0f8-9067de9c6ccb.png)
![Screenshot 2022-08-28 at 11 16 39 AM](https://user-images.githubusercontent.com/31209824/187090285-f486c957-f464-481b-89a5-466b423f66e0.png)
![Screenshot 2022-08-28 at 11 16 49 AM](https://user-images.githubusercontent.com/31209824/187090286-fc0cec71-dc9d-4e0a-aa25-dbc3c3a615a5.png)
