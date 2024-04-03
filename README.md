# Food Sales Predictions 
### Sales prediction for food items sold at various stores. 

Eya GONGI

## Business Problem 

Companies operating in the food industry look for estimating future saling.   
There are so many benefits to know which and how many items to sell:

      +  Minimizing Stocked and Expired Products
      +  Avoiding Missed Sales Opportunities 
The goal of this project will be to help the retailer understand the properties    of products and outlets that play crucial roles in increasing sales. 
## Data Source 

Food Sales Data 

https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

## Data Dictionary 

Here is the Data Dictionary of the dataset 
[ ![image](https://github.com/eyaGONGI/sales_prediction/assets/118536575/d62c7263-17b9-44f1-9228-8f8a7996fd3c)
 ]

 

## Methods 
### Data preparation steps 
* Data Shape
* Data types
* Drop duplicated data
* Adress the missing values: impute missing values of 'Item Weight' by the mean and the most frequent value of 'Outlet Size'
* Fix inconsistent data
* Summary statistics of numeric data
  
## Results 
During the exploratory data analysis, a histogram was visualized for each numeric datatype column. 

### Outlet Size Graph

![explanatory 1 ](https://github.com/eyaGONGI/sales_prediction/assets/118536575/2ee35419-cab2-4158-b5e6-8cade25961ab)

The majority of outlet articles are medium size

### Outlet Establishement Year

![Capture d'écran 2024-04-02 145156](https://github.com/eyaGONGI/sales_prediction/assets/118536575/4354b7c8-33b9-4be7-9ed6-3eff851c106a)

This graph shows the year that outlet items were created. The sales team can conclude the sales rate of each year for sales increasing work.  

### Features Correlation
The heatmap shows the correlation between data columns. 

![explanatory 4](https://github.com/eyaGONGI/sales_prediction/assets/118536575/c0b09c69-9026-4589-bc95-025d53ed225c)

## Model
### Machine Learning Models:

* Linear Regression Model
* Regression Tree Model
  
### Metrics of evaluation:

* Linear Regression Model:
  
    R^2:
  
       -> Training set: 0.561
       -> Testing set: 0.567

    RMSE:
     
       -> Training set: 1298226.806
       -> Testing set:  1195495.98
  
* Regression Tree Model

  
    R^2:
  
       -> Training set: 1.0
       -> Testing set: 0.174

    RMSE:
  
       -> Training set: 0.0
       -> Testing set: 2278362.376
  
  The final model chosen was Regression Tree Model because the results shows that the model performs highly well on trainnig set.
  To improve the performance  with testing set, we have to tune the model.

  Linear Regression Model is not the best model for the dataset because the predictions are about 50%.
  

## Recommendations 

Overall the best model is definitely the tuned Regression Tree model. 

## Limitations & next steps 

Tuning the model to improve metric values for testing set. 

## For further information 

For any additional questions,   

please contact: 
eya.elgongi@gmail.com 
   
