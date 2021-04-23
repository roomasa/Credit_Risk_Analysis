# Credit_Risk_Analysis


### Overview of the loan prediction risk analysis:

The purpose of this analysis is to develop machine learning models to predict credit risk and to compare the performace of the various models. There is also an imbalance in representation of the the two groups: i.e. the low risk and high risk loans requiring us to use additional sampling and ensemble techniques to improve the performance of the models. 

### Results:

See below the accuracy scores and the precision and recall scores of all six machine learning models (15 pt)

**  Model Name 	          Accuracy 	    Precision (high risk, low risk)	      Recall (high risk, low risk)**
1. Random Oversampling:	0.63	        0.01, 1.00	                          0.60,0.66
2. SMOTE oversampling:	0.62	        0.01, 1.00	                          0.60,0.64
3. Undersampling:	0.62	              0.01, 1.00	                          0.59, 0.43
4. Combination: 	0.51	              0.01, 1.00	                          0.69, 0.54
5. Random Forest:	0.995	              0.58, 1.00	                          0.32, 1.00
6. Easy Ensemble:	0.93	              0.07, 1.00	                          0.92, 0.93
7. 
8. ![image](https://user-images.githubusercontent.com/75815560/115932474-a48e6100-a452-11eb-91c9-be3244df90d6.png)



### Summary:

There is a summary of the results (2 pt)

There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
