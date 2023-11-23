# Travel Insurance Prediction Using Machine Learning
This project centers around the application of machine learning to train a model for accurate categorization of individuals into two distinct groups: those who are likely to purchase travel insurance and those who are not. We have followerd a few steps during this project:
1. Formulated the problem.
2. Conducted EDA to uncover patterns.
3. Visualized findings.
4. Applied statistical testing procedures.
5. Trained multiple ML models.
6. Analyzed model performance.
7. Selected the final model.

## Data Source
We're using "Travel Insurance Prediction Data" from Kaggle, which can be found [here](https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data).

## Results and Findings
- We have found that most of the features don't allow for optimal separation of target variable.
- Even though most features do not separate target variable well in 2D or 3D space, almost all but two of them are statistically significant.
- We ended up selecting a model with average precision, recall and f1-score of 0.69, and accuracy of 0.72, leading to uncertainty of whether the model would actually applicable (more on that in "Future Work").

## Future Work
- Better formulation of the problem would have allowed us to make a better decision when it came to training the models: should we emphasise the class '1', the people who bought the insurance more often and assign it more aggressive weight, or should we keep it balanced as we did. Knowing, what's more important to us, making less mistakes, or having more people buy travel insurance, would've helped in this decision. Also having more information on the economy part of the problem, would allow us to tell whether we would want to use the final logistic regression model, however, I believe, that such cost-benefit analysis is slightly out of scope for this project.
- More extensive statistical inference part. We've only used chi-square and Mann-Whitney U tests to test for our features' significance.
- Better feature engineering or transformations to the existing data. Some better features that would allow us to better separate the two classes or achieving similar result by transforming the independent features.
- Trying out training the models with more features. We've used only 4 features to train our models, perhaps using more would've resulted in better separation of our classes which would have possibly lead to better recall and other metrics.
- Use of pipelines to handle transformations and flow of data.

## Usage
While not intended to, feel free to download and run the notebook on your own machine.
