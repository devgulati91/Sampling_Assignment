# Sampling_Assignment
 I have used five sampling techniques on a 'credit card fraud detection' dataset and then applied five Machine Learning classification models on each sample to find out which 'Model&sampling technique' combination gives us the best accuracy.

5 sampling Techniques used are:

Random Under Sampler\ 
Random Over Sampler\
SMOTE\
TOMEK links\
Near Miss\
\
The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: n = sample size Z = z-value (for 95% confidence interval, Z = 1.96) p = proportion of the minority class (taken as 0.5 for a balanced dataset) m = margin of error (taken as 0.1 for a sample size of 1000)

 5 models applied are:\

Naive Bayes\
Support Vector Machine\
Decision Tree Classifier \
Random Forest Classifier\
Extra Tree Classifier \


the accuracy of the applied model using the respective sampling technique is tabulated as under:
<img width="410" alt="image" src="https://user-images.githubusercontent.com/111454531/219962620-c2f361f0-19c0-495a-88a7-59881ea8946c.png">

As we can see from the above  table that the Maximum Accuracy obtained is 99.35% using:

Naive Bayes with Random Over Sampler, Smote and Tomek\
Random Forest Classifier with Random Over Sampler, Smote and Tomek\
Extra Tree Classifier with Random Over Sampler, Smote and Tomek\

