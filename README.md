# Classification Model

We built a Classification model that can detect if a loan is likely to default based on a number of input features . 

Since our Data is is labeled, We stuck to Supervised Machine Learning Models 

In total, we build 3 different model and compared their and tested them using balanced data. 

## Imbalanced Data 

The issue with our Data is that the number of Healthy loans outweigh the number of Default loans causing a large Imbalance in out data. We used 3 different Data Scaling methods on our models to balance the data set. 

* RandomOverSampler
* SMOTE-ENN (Synthetic Minority Over-sampling Technique - Edited Nearest Neighbor)- Replaced Central Clustroids . 
* Standard Scaler 

One Hot encoder was used to encode our categorical Variables. We combined the numerical and encoded Data Frames for out Training and Test Data Sets.

### Logistic Regression - Classification Report
![alt=""](Images/
### Random Forest - Classification Report 
![alt=""](Images/



----------------------------------------------------------------------------------------------------------

# Presentation:
https://docs.google.com/presentation/d/1LtQe-u_1z7vdbRfI9t3v6zy0mwx0zS0FTXAJl0sK4HQ/edit?usp=sharing
