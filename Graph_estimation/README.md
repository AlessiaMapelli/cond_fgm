# Content of cFGGM_functions

## Function: Weighted_lasso_selection_cGGM
#### 	Input data
-	  x: dataframe protein data (n x p)
-		known_ppi: matrix prior known PPI matrix
-		covariates: dataframe covariates to be included (n x q)
-		scr: boolean optional prescreening based on correlation between the proteins
-		gamma: numeric correlation threshold to be used in the prescreening. If NULL the 10% quantile is used
-		lambda: numeric penalization factor in the Lasso regression
-		weight: numeric multiplicative factor for the penalization when prior knowledge is not available
-		verbose: boolean prints comment in the code
-		eps: numeric zero approximation![image](https://github.com/user-attachments/assets/3fcd79c3-e746-41fd-babd-5dae401ed8bd)

