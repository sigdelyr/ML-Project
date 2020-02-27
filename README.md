# ML-Project
Our Data sources were Yahoo Finance and the Securities and Exchange Commission site and ETL done on the data is were Web Scraping and Datetime convention.
We used two models, linear Regression and Random Forest Regression. 
  *  We fitted the Linear Regression model to previous number of samples value and used that model to predict the stock value on the current   day.
      * We found that the Root Mean Squared Error is 3.953 and the R^2 is 0.985 on the test set using 5 number of samples.
  *  We used Random Forest Regression to get a more stable and accurate prediction of the next day stock value.
	    * We found the R^2 to be 0.98 and the Mean Squared Error to be 4.64
