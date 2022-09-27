# Go Beyond Binary Classification with Multi-Class and Multi-Label Models
 
Often when you start learning about classification problems in Machine Learning, you start with [binary classification](https://www.dataknowsall.com/classification.html) or where there are only two possible outcomes, such as *spam* or *not spam*, *fraud* or *not fraud*, and so on. We have **Multi-class** and **multi-label** classification beyond that. Let's start by explaining each one.

**Multi-Class Classification** is where you have more than two categories in your target variable (`y`). For example, you could have *small*, *medium*, *large*, and *xlarge*, or you might have a rating system based on one to five stars. Each of these levels can be considered a class as well. The objective of this strategy is to **predict a single class** out of the available classes.

**Multi-Label Classification** is slightly different. Here you have more than two categories available as well, but instead of choosing only a single class, the objective of this strategy is to **predict multiple classes** when applicable. This strategy is useful when you have multiple categories related to each other. One of the best examples I've seen is when this is used in a tagging system. For example, Medium articles can have multiple tags associated with them. This particular article might have `machine learning`, `data science`, and `python` as tags. 

Before you start, If you want a deep dive on Binary Classification, check out my article: [Everything You Need to Know to Build an Amazing Binary Classifier](https://www.dataknowsall.com/classification.html)

Read more here: https://www.dataknowsall.com/multiclass.html
