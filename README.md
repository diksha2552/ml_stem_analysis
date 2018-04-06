# ml_stem_analysis

Data: https://data.world/education/2010-federal-stem-inventory/file/2010%20Federal%20STEM%20Education%20Inventory%20Data%20Set.xls
 
Stage 1:
1) Calculate % growth of funding between year 2008 & 2009.
2) If funding is positive, tag it as 1, if funding is negative tag it as 0. This is the target variable.
 
Stage 2:
1) Create graphs of univariate distribution of all non funding variables and share on a jupyter notebook. Just FYI - Funding FY2008, FY2009, FY2010 are the "funding variables"
2) Calculate mutual_info_score of target variable created in stage 1 & ALL non funding variables and share on a jupyter notebook.
 
Stage 3:
1) Divide data into train & test samples. (70-30 split)
2) Select features & build xgboost model. 
3) Write testcases on all user defined functions using pytest framework.
