# Insurance-Claim
An Insurance firm providing tour insurance is facing higher claim frequency. Data is collected from the past few years. Made a model which  predicts the claim status using CART, RF &amp; ANN and  compare the models' performances in train and test sets.

# EDA
  Dataset has 10 variables and 3000 instances. 2 variables are float type and 2 are integer type. There are 6 object-type variables which need to be converted to numeric form.
  From the above data, it is evident that no null values are present in the data. The shape of the dataset is 3000,10.
  
  Using the describe() function in Python, a summary of all the parameters can be obtained. Asia seems to have the most insurance claims.
  After the removal of the duplicated data, the outliers were calculated. The outliers were not treated since all numeric values have them and can be taken care of in random 
  forest classification.
  
  Pairplot was performed to check continuous variables
  Heatmap was performed to check correlation
  
  Decision tree in Python can take only numerical / categorical colums. It cannot take string / object types.
  The feature statement loops through each column and checks if the column type is object then converts those columns into categorical with each distinct value becoming a category.

## Split the data into test and train, to build classification model CART, Random Forest, Artificial Neural Network.

  Built a decision tree and found the variable importance and predicted the test data.
  Added tuning parameters to regulise the decision tree and found the variable importance again.
  Found the prediting probabilities
  
# Random Forest

  Treated the model for outliers 
  Predicted test and train data with RF model
  
# MLP Classifier

  Predicted using the training and testing data
  
# ROC_AUC
  Checked the performance of Predictions on Train and Test sets using Accuracy, Confusion Matrix, Plot ROC curve and get ROC_AUC score for each model.
  
# Analysis

  Looking at the model, more data will help us understand and predict models better. Streamlining online experiences benefitted customers, leading to an increase in conversions, which subsequently 
  raised profits. 
   As per the data 90% of insurance is done by online channel. Other interesting fact, is almost all the offline business has a claimed associated with it. 
   Need to train the JZI agency resources to pick up sales as they are in bottom, need to run promotional marketing campaign or evaluate if we need to tie up with alternate agency.
   Also based on the model we are getting 80% accuracy, so we need customer books airline tickets or plans, cross sell the insurance based on the claim data pattern. Other interesting fact is more sales 
  happen via Agency than Airlines and the trend shows the claim are processed more at Airline. So, we may need to dive deeper to understand the workflow.
  Key performance indicators (KPI) will increase customer satisfaction which in fact will give more revenue, combat fraud transactions, deploy measures to avoid fraudulent transactions at earliest as 
  well as optimize claim-recovery method. It will also reduce the claim handling costs
  
  
