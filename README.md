# UW-Madison FA21 STAT 451
Final project repo of Group 26 owned by Zhaoxing (Bella) Wu.

Professor Name: Sebastian Raschka

## Project Name
Predicting the Success of Telemarketing in Subscription of a Term Deposit Using Machine Learning Methods.

## Project Contribution
  - Arden Kim: worked on the Abstract, Introduction, Related Work, and Proposed Method sections in the paper.
  - Zhaoxing (Bella) Wu: coded classifiers together and parameter tuning and finished writing the Experiment and Conclusion sections in the paper.
  - Wenxuan (Emma) Chen: coded classifiers together and parameter tuning and worked on the Abstract, Introduction, Related Work, and Proposed Method sections in the paper.
  - Mengwei Sun: found the original dataset online, cleaned up the data, prepared training, and tested the data split for further analysis. Completed
the Result and Discussion sections in the paper.

## Project Abstract
This project aims to help banks predict whether a client will subscribe to a term deposit marketed through the channel of phone calls as well as improve the marketing conversion rate by targeting a certain population of clients. The dataset used[2] is from a direct marketing campaign of a Portuguese banking institution, with 41188 observations, 20 features, and a binary target variable of a client’s subscription response. With logistic regression as the baseline model, this project compares KNN, Adaboost, Xgboost, Decision Tree, and Random Forest in terms of accuracy, recall, precision, and F1 scores. The results show that a balanced Decision Tree classifier is highly recommended for prediction and banks should aim at the population with higher income, more advanced educational background, and age group of twenties, thirties, sixties and seventies when advertising through phone calls.

## Data Cleaning and Training

<p float="left">
  <img src="https://github.com/zwu363/UW-Madison-FA21-STAT451/blob/main/figure/flow_fs.png" width="350" />
  <img src="https://github.com/zwu363/UW-Madison-FA21-STAT451/blob/main/figure/flow_mf.png" width="350" />
</p>

Figure: **Left**: a flowchart of feature selection process. **Right**: a flowchart of classifier training process.

## Performance Evaluation
<p float="left">
  <img src="https://github.com/zwu363/UW-Madison-FA21-STAT451/blob/main/figure/eval_auc.png" width="350" />
  <img src="https://github.com/zwu363/UW-Madison-FA21-STAT451/blob/main/figure/eval_f1.png" width="350" />
</p>

Figure: **Left**: ROC AUC for each classifier trained on oversampling training set. **Right**: F1 score in each classifier.

<p float="left">
  <img src="https://github.com/zwu363/UW-Madison-FA21-STAT451/blob/main/figure/vis_job.png" height="200" />
  <img src="https://github.com/zwu363/UW-Madison-FA21-STAT451/blob/main/figure/vis_edu.png" height="200" />
  <img src="https://github.com/zwu363/UW-Madison-FA21-STAT451/blob/main/figure/vis_age.png" height="200" />
</p>

Figure: Bar charts of subscribing lease terms for different job groups (left), education groups (middle), age groups (right).
