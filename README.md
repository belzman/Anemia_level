# Predicting the level of anemia among Ethiopian pregnant women using homogeneous ensemble machine learning algorithm
# Background
More than 115,000 maternal deaths and 591,000 prenatal deaths occurred in the world per year with anemia, the reduction of red blood cells or hemoglobin in the blood. The world health organization divides anemia in pregnancy into mild anemia (Hb 10–10.9 g/dl), moderate anemia (Hb 7.0–9.9 g/dl), and severe anemia (Hb < 7 g/dl). This study aims to predict the level of anemia among pregnant women in the case of Ethiopia using homogeneous ensemble machine learning algorithms.

# Methods
This study was conducted following a design science approach. The data were gathered from the Ethiopian demographic health survey and preprocessed to get quality data that are suitable for the machine learning algorithm to develop a model that predicts the levels of anemia among pregnant. Decision tree, random forest, cat boost, and extreme gradient boosting with class decomposition (one versus one and one versus rest) and without class decomposition were employed to build the predictive model. For constructing the proposed model, twelve experiments were conducted with a total of 29,104 instances with 23 features, and a training and testing dataset split ratio of 80/20.

# Results
The overall accuracy of random forest, extreme gradient boosting, and cat boost without class decompositions is 91.34%, 94.26%, and 97.08.90%, respectively. The overall accuracy of random forest, extreme gradient boosting, and cat boost with one versus one is 94.4%, 95.21%, and 97.44%, respectively. The overall accuracy of random forest, extreme gradient boosting, and cat boost with one versus the rest are 94.4%, 94.54%, and 97.6%, respectively.

# Conclusion
Finally, the researcher decided to use cat boost algorithms with one versus the rest for further use in the development of artifacts, model deployment, risk factor analysis, and generating rules because it has registered better performance with 97.6% accuracy. The most determinant risk factors of anemia among pregnant women were identified using feature importance. Some of them are the duration of the current pregnancy, age, source of drinking water, respondent’s (pregnant women) occupation, number of household members, wealth index, husband/partner's education level, and birth history.
# Author
@Belayneh Endalamaw Dejene
@Tesfamariam Mulugeta Abuhay
