# PatentAssignmentPrediction
### prdict patent assignment with PCA and logistic regression

## Process
1. Crawling the patent from USPTO & Google Patents
  * Crawling data from USPTO & Google Patents
  * query == 'CPCL/G06Q and ISD/1/1/2005->1/1/2017'
2. Preprocessing
  * Set the y & x columns
3. Basic statistical analysis
  * Drawing PairPlot with Seaborn
  * Checking Multicollinearity : Deleting independent variable
4. Modeling
  * PCA : Choosing the best PC
  * LogisticRegresssion : Predicting Assignment==1 / NotAssignment==0
5. Result
  * summary
  * limitation
