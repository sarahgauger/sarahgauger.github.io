## My Project

For my final project, I have applied machine learning techniques to investigate a data set that holds a correlation between blood work that indicates liver disease and the corresponding number of alcoholic drinks consumed per day for each test point. I will compare my findings with the national board of health’s recommendation of drinks per day to see how they compare to the number of drinks per day in the data that indicates a risk for liver disease. I am interested to see if the number of drinks is over or under the national recommendation for a healthy system and liver. Training this model to predict the percentage of adult men at risk for liver diseases will allow us to see how far above or below the nationals official guidelines to how many drinks a day for adult men. The national guideline for alcohol consumption limits intake to 2 drinks per day. The target variable in the dataset represents the number of half-pint equivalents of alcoholic beverages drunk per day for adult men. So, I will use my model to compare the value of these two groups, and make inclinations from the results. 


According to the National Center for Drug Abuse Statistics, “10% of Americans over the age of 12 have Alcohol Use Disorder”. They also stated that on average, over 140,000 Americans die yearly from the effects of alcohol. Men have been shown to be at a much higher risk of alcohol abuse than women. This topic has been a long held national conversation, all in efforts to limit alcohol in people’s lives. 

I will be using a data set from the UC Irvine Machine Learning Repository, titled, "Liver Disorders". The data set has 5 varibales with are bloodtest that can indicate liver disorder in a subject. These data points are accompanied with 


***

## Introduction 

Here is a summary description of the topic. Here is the problem. This is why the problem is important.

There is some dataset that we can use to help solve this problem. This allows a machine learning approach. This is how I will solve the problem using supervised/unsupervised/reinforcement/etc. machine learning.

We did this to solve the problem. We concluded that...

## Data

Here is an overview of the dataset, how it was obtained and the preprocessing steps taken, with some plots!

![](assets/IMG/datapenguin.png){: width="500" }

*Figure 1: Here is a caption for my diagram. This one shows a pengiun [1].*

## Modelling

Here are some more details about the machine learning approach, and why this was deemed appropriate for the dataset. 

The model might involve optimizing some quantity. You can include snippets of code if it is helpful to explain things.

```python
from sklearn.ensemble import ExtraTreesClassifier
from sklearn.datasets import make_classification
X, y = make_classification(n_features=4, random_state=0)
clf = ExtraTreesClassifier(n_estimators=100, random_state=0)
clf.fit(X, y)
clf.predict([[0, 0, 0, 0]])
```

This is how the method was developed.

## Results

Figure X shows... [description of Figure X].

## Discussion

From Figure X, one can see that... [interpretation of Figure X].

## Conclusion

Here is a brief summary. From this work, the following conclusions can be made:
* first conclusion
* second conclusion

Here is how this work could be developed further in a future project.

## References
[1] DALL-E 3

[back](./)

