# Kaggle Learning
## An overview
With a bit of spare time on my hands, I felt the sudden urge to start my journey into some data science.
Hence began my journey through the Kaggle courses, namely:
- [Titanic Tutorial](https://www.kaggle.com/competitions/titanic)
- [Intro to Deep Learning](https://www.kaggle.com/learn/intro-to-deep-learning)

Hopefully, it'll be a fun experience, where I can learn the basics of a variety of models, but also improve my skills working with libraries such as NumPy, Pandas, etc.

This little quest will also be my first time working with Git, so that's exciting!

## Titanic
### The target
Given a dataset of specific information about passengers aboard the fateful Titanic incident, and if they survived or not - build a model to predict the survival of many other passengers given another unseen dataset.

### The data
In the [data](datasets/titanic/), the known factors of each passenger are:
- PassengerID
- Survived
- Passenger Class (Pclass)
- Name
- Sex
- Age
- Number of siblings and spouses aboard (SibSp)
- Parch
- Ticket
- Fare
- Cabin
- Embarked

### The model
The model used is a [RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) part of the [scikit-learn](https://scikit-learn.org/stable/) library.

With the built in features of the RandomForestClassifier, it was relatively easy to fit the model against the [training data](datasets/titanic/train.csv), then predict the survival of each passenger in the [testing data](datasets/titanic/test.csv).<br>
This model has an approximate accuracy of 77%.