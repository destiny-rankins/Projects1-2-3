# Project2
This project is a regression analysis to predict outcome of tracheostomy to guide the indication criteria and timing of tracheostomy placement. 
There is a quarto markdown file included in the . The analysis demographic and clincical data collect at four different timepoints; birth,
36 weeks post-menstal age, 44 weeks post-menstral age, and discharge. To predict the outcome, a logistic model, a lasso model, and a ridge model were 
develop using five imputed data set. Multiple imputation was implemented using the mice() function. To assess the performance and accuracy of each model,
discrimination and calibration methods were used. The ROC-AUC and Brier Score were used to assess the model. Furthermore, calibration on predicted probabilities
conducted.
