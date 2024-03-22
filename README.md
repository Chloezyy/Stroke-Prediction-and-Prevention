According to the World Health Organization (WHO) stroke is the 2nd leading cause of death
globally, responsible for approximately 11% of total deaths. It is necessary to establish a good
model and find the important factors affecting stroke so as to achieve the role of prevention and
research.

For our research, we will develop a classifier that predicts the probability of whether or not
someone will have a stroke based on relevant input parameters. Healthcare practitioners will be
able to identify which patients are at high-risk for a stroke, prescribe proper treatment, and save
lives. Such prevention can help save hospitals millions of dollars in stroke-recovery
rehabilitation and long-term care. For our business case, we will attempt to quantify the expected
value savings of implementing our model for such healthcare institutions.

This project mainly uses supervised learning algorithms to analyze and predict data. We will
train the dataset to various models, including but not limited to logistic regression, Bagging,
KNN, random forest, SVM, and Neural Networks (ANN). By comparing the accuracy, AUC,
RMSE and other relevant parameters of these algorithms, we will get a best and most applicable
model which can fit the data very well.
Meanwhile, we will rank the importance of each predictor by using <varImp> function in
<caret> package in R to track the changes in model statistics for each predictor. This step is
crucial since predictors that has large impact on models might be considered the key factor for
stroke. Hospitals will focus on these factors in patients to prevent stroke.
