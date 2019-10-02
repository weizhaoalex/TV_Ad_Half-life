# TV_Ad_Half-life
Estimate the half-life of TV advertising.<br/>
Half-life is the time period that TV advertising effectiveness dropped to 50% of the original value. This decay rate is used to estimate the carryover effect of TV advertising.<br/>
The method introduced here is:<br/>
1. Use a loop to create adstock variable with different half-life.
2. Use a loop to run a regression model with each adstock and target variable,find the one can maximize R-sq.
3. Make sure the adstock found from the step above doesn't have a negative correlation with target variable.
