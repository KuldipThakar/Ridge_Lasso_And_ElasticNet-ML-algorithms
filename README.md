1. Ridge Regression (L2 Regularization)
Full Name: Ridge Regression
Description:
Ridge regression is a linear regression model with L2 regularization, which adds a penalty equal to the square of the magnitude of coefficients. This prevents overfitting by shrinking the model coefficients, making it more robust to multicollinearity.

2. Lasso Regression (L1 Regularization)
Full Name: Least Absolute Shrinkage and Selection Operator (Lasso)
Description:
Lasso regression uses L1 regularization, which adds a penalty equal to the absolute value of the coefficients. This has the effect of shrinking some coefficients to exactly zero, effectively performing feature selection.

3. Elastic Net Regression (L1 + L2 Regularization)
Full Name: Elastic Net Regression
Description:
Elastic Net is a combination of L1 (Lasso) and L2 (Ridge) regularization. It overcomes the limitations of Lasso when features are highly correlated and improves generalization.

Algorithm          Regularization Type	           Feature Selection	           Works Best When
Ridge	            L2(Squared Coefficients)	          No	                    Features are correlated

Lasso	            L1(Absolute Coefficients)         	Yes                    (Some coefficients become zero)	Sparse models with fewer important features

Elastic Net	      L1 + L2 (Combination)	              Yes                    (Better than Lasso in correlated features)	Large number of correlated features
