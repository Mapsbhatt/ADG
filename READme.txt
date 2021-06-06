- Try some of the inbuilt function of pandas, numpy, seaborn and matplotlib



- Use of different graphs



- Pearson Correlation: -1, -1 , 0 refers to correlation coefficient of correlation between parameter with having +ve relation, -ve relation and no relation respectively
P-value:- 
# <0.001- Strong
# <0.05- Moderate
# <0.1- Weak 
# >0.1- No Certainity



- Linear Regression
  - Spliting data into test and train, using a mask and in built function.
  - Predicting the output, using the trained data
  - Comparing the acquired results to the ideal result, using evaluation metrics(r^2 score)
  - Use of residplot- Residual plot is the plot of the error, the Y-axis plot the difference between the predicted value and the       actual value.If there some relation in the residplot then the parameters predicted values do not match the actual values,         ideally the graph should be a straight line passing through X-axis. A parabola or increasing graph is not a good sign.
 
 
 
 
- Polynomial Regression
  - Using a polynomial equation, getting its coefficients and training it. 
  - Testing it to get determine its accuracy. 




- K-nearest Neighbour
  - Using K- nearest neighbour method to predict the output.
  - Testing for which value of 'k' is the predicted value most accurate.
  
  
  
  
- Decision Tree  
  - Decison Trees are made using recurssive partitioning to classify data.
  - After partitioning the predictiveness of the parameters suggest the outcome.
  - If the entropy is less(ideally 0), then the chances to correctly predict increases.
  -Each partitioned parameter is called as a node.
  
  - Entropy= p(A)log(p(A))-p(B)log(p(B))
  
  -Have premade package to calculate entropy
  
  - The parameters need to be compared before we consider them for prediction on the basis of which have less entropy, or which gives more pure nodes
  - Now, in order to compare the given attribute, information gain is used, which is the entropy before splitting the node - net weighted entropy after splitting the node.
  - More the information gain better will the outcome be.
  - After the first split the process is continued, until we get a pure node.
  - 
  
  
  
  
- Logistic Regression
  - Logistic Regression is analogous to linear regression, the core differnece being that, in linear regression we use continuous range of values to train and predict the model, whereas in logistic regression we use independent variables to predict categorically defined data(may be binary/ may be multi-class defined categorical data.)
  - Predicting is basically defined by use of probability. 
  - Linear Regression model fail to give the probablity of a given event to occur. It can only specify the events in classes, based on their set thresholds. Similiar to a step function in maths.
  - In order to obtain a more smoother grapha as compared to sharp changing step function we use sigmoidal/logistic function, to calculate probablity.
  - Output of a sigmoidal function always varies between 0 and 1.
  - Use and how to calculate cost function.
  