# SonarRockMinePrediction
# WORKFLOW
![WorkFlow](https://github.com/CatalystsReachOut/SonarRockMinePrediction/blob/master/Screenshot%202022-09-02%20at%2002.00.34.png)<br>
## Collect Sonar Data 
Laboratory setup experiment can be done where sonar is used to send and receive signals. There is far difference between signals received from mines and rocks. Because mines will be made up of metal. So, we collect this data which is nothing but the sonar  data obtained from a rock and a metal cylinder. 
<br>And later, we use this sonar data and feed it to our machine learning model. And our model will predict whether the object is made up of metal or it is just a rock. This is the principle we are going to use in our prediction.
<br><br>

## Data Preprocessing 
We must process data for better results. In preprocessing, we do cleaning, filling missing values etc.<br><br>

## Train Test Split 
After that, we will train our model with 80-90% of training-data and 10–20% will be used to test-data. And evaluate our model with the help of test-data.<br><br>

## Logistic Regression Model 
Why Logistic Regression Model ? Because, this model works very well for [Binary Classification Problem](https://machinelearningmastery.com/types-of-classification-in-machine-learning/). It is a Binary Classification Problem (Rock or a Mine). This is a Supervised Learning Algorithm.<br><br>
 
# Conclusion
![Final Overview](https://github.com/CatalystsReachOut/SonarRockMinePrediction/blob/master/Screenshot%202022-09-02%20at%2002.07.51.png)
