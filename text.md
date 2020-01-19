We developed an efficient alternating updating algorithm for generalized tensor-response regression given covariates on multiple modes. The package contains three functions: `tensor_regress` to implement tensor regression model. The inputs are response tensor, multiple covariate matrices, and a desired Tucker rank. The outputs is a constrained MLE for the coefficient tensor ; `sele_rank` to estimate the tucker rank of coefficient tensor based on BIC criterion; `sim_data` to generate response tensor and multiple covariate under different settings.



This project aims at investigating the connection between soccer strategies and the result of the game in Premier league data. The research helps us understand how strategies would work considering teams’ own style and their opponents’ style. The model uses PCA and clustering on information extraction in assessing the different aspects (attack, defence, domination) of a team. Then we use softmax or logistic regression and their statistical meaning to explain the relationship between game results and different features, in which we also take the both teams’ style in a game to explain our model. Finally, we use the most intuitive way–decision tree to classify the model, and try to find corresponding rule to explain our idea. In conclusion, we put much emphasis on the model explanation in this project, and get interpretable results.
