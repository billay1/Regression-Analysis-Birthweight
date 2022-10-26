# Regression-Analysis-on-Birthweights
Regression analysis to determine factors affecting a newborn weights.
•	Cleaned the data and replaced missing values with either mean or median based on data skewness
•	Compared skewness of original data y and log y variables with bar charts to choose the best dependent variable 
•	Forecasted which factors and their degree of impact on the weight of a newborn using regression models like Ordinary Least squares, Lasso, ARD and KNN regressiosn and chose optimal model based on training and testing data sets R2 and their gap.

The following conclusions were derived:

- Daily Consumption of bad substances like cigarettes and alcohol by the mother is more likely to decrease the weight of the baby at birth by <strong>8g</strong>. <br>
- Age is a significant factor affecting the weight of the baby. The older the parents, especially the mother, the less fertile she gets and the more the newborn weight is negatively affected. We have a proportion of <strong>0.23g</strong> of weight lost per year of age after 35 years old.<br>
- Nonetheless, some factors positively impact the weight of the newborn like the level of education of parents with an influence of <strong>+1.35g</strong> as the years of studies increases. It is presume that parents who studied more have deeper knowledge of the human body and how to behave to get the baby born healthy, going from the diet to medical care. <br> As far as medical care is concerned, the last factor in the prediction, prenatal care which is a combination of the prenatal visits and the month where the visits started, has a positive impact on the weight of the newborn with <strong>+2.8g</strong> in more for high frequencies of visits and the sooner they start.


