# Project 1
This project is an exploratory data analysis on the smoking cessation. The externalizing, substance abuse and internalizing behaviors of 
parent and children are examined by smoking status. The different smoking statuses include parents that smoked during three trimesters of 
pregnancy, smoked postpartum, and were exposed to smoke. A R mardown file is included.

# Project2
This project is a regression analysis to predict outcome of tracheostomy to guide the indication criteria and timing of tracheostomy placement. 
There is a quarto markdown file included in the . The analysis demographic and clincical data collect at four different timepoints; birth,
36 weeks post-menstal age, 44 weeks post-menstral age, and discharge. To predict the outcome, a logistic model, a lasso model, and a ridge 
model were develop using five imputed data set. Multiple imputation was implemented using the mice() function. To assess the performance and 
accuracy of each model,discrimination and calibration methods were used. The ROC-AUC and Brier Score were used to assess the model. Furthermore,
calibration on predicted probabilities conducted.

# Project 3
This project includes a transportability anysis where a logistic regression model was developed on the source population Framingham study
data to predict the probability of experiencing the outcome of cardiovascular disease and evaluated in a new target population (NHANES 
data). The NHANES data sample did not include the observed outcome variable for cardiovascular disease. The Framingham study data was split 
into a training set for model development and a test set to validate the model, or measure how the model performs on unseen data. The Brier
score was then used to measure the accuracy of predicted probabilities. The model performance was estimated in the new target population by
creating an outcome indicator variable "S" where,  S=1 indicates the probability of being in the Framingham study data and S=0 indicated the
probability of being in the NHANES data. The inverse-odds weights were used to calculated the estimate for the Brier risk. The target population 
data was simulated using individual level data from the NHANES survey and the model's performance evaluated from the estimator for the Brier risk.
