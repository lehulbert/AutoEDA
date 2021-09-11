# AutoEDA

Automated EDA for general data sets as well as for classification  & regression problems, specifically. 

Requirements: Tableau access

Steps: 
1) Specify level of detail variables, target variable, target variable type, and path to data file in params.yaml. 
2) Run eda.ipynb to transform the data. Outs 3 excel files - one for plotting categorical features, one for plotting continuous features, and for for generating a correlation matrix. 
3) Edit the Tableau data connections to put to the files output from step 2. 

Sample visuals below use the House Prices & Titanic datasets

## Sample Visuals for General EDA
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Categorical%20Summary.png?raw=true)  
  
    
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Categorical%20Bar%20Charts.png?raw=true)  
  
    
Continuous feature summary: 
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Continuous%20Summary.png?raw=true)  
  
    
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Continuous%20Distributions.png?raw=true)  
  
    
Correlation matrix: 
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Correlation%20Matrix.png?raw=true)  
  
    
Correlation matrix (focused view): 
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Correlation%20BarChart.png?raw=true)  
  
    
## Sample Visuals for data with Binary Target  
Binary target variable summary: 
  
    
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Cat%20Target%20Summary.png?raw=true)  
  
    
Binary target variable vs. categorial features:  
(In this example, we can there are more men in the dataset, but females were more likely to survive than men)   
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/cat%20feat%20vs.%20cat%20target.png?raw=true)  
  
  
Binary target variable vs. continuous features:  
(higher fares are associated with greater chance of survival)  
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Cont%20Feat%20vs.%20Cat%20Target.png?raw=true)  
  
    
## Sample Visuals for data with Continuous Target 
Summary of the target variable:  
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Cont%20summary.png?raw=true)  
  
    
Continuous target vs. continuous features:   
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Scatterplot.png?raw=true)  
  
    
Continuous target vs. categorical features:   
In this example, 1 and 4 bedroom houses have the most price variability. Zero bedroom houses are rare, but surprisingly pricy. We'd want to look into that. Roughtly, prices climb as number of bedrooms increases.   
![alt text](https://github.com/lehulbert/AutoEDA/blob/master/Screenshots/Cat%20Feat%20vs.%20Cont%20Target.png?raw=true)  
  

