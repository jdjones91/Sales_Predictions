# Sales Predictions: My first Data Science Project at Coding Dojo.
### Files 1-4 are examples of data cleaning and visualization. Files 5 and 6 are axamples of pre-processing data and building 2 Machine Learning Models to predict sales.
### Author: James Jones
# Business Problem: 
Can we predict product sales for a Grocery Store Chain?
### We want to predict 'Item Sales' with data such as 'Item Visibility', 'MRP', 'Item Weight', 'Fat Content' etc.

## I used Data cleaning an visualizations to gether insights into the data. I leaned about correlations, sales distribution across store types, and present graphical explantions primarily within Sales Predictions 4. These methods were used to more deeply understand the data.
## I created preprocessors for machine learning models. This is necessary for the data to be interpreted by a computer. Two models were then used, so I could choose the better of the two, as it is always better to have multiple options.

![Screen Shot 2022-09-22 at 1 08 44 PM](https://user-images.githubusercontent.com/109368648/191831257-0d401868-96cb-4796-a0ad-27d32fa6847d.png)

Using visualization like the one above, I was able to see patterns in the data

And using a heatmap, I was able to visualize any correlations that existed within this data set

<img width="465" alt="Screen Shot 2022-09-22 at 1 12 25 PM" src="https://user-images.githubusercontent.com/109368648/191831863-647e00ce-b07f-4ff6-8657-9117ffd4da54.png">

### Finally, I created two predictive models: A Linear Resgression Model, and a Decision (Regression) Tree

## Linear Regression Model: metrics on Testing data
I calculated an R2 score of 0.567, suggesting that this model can explain approx %56.7 of our data in the prediction.
I calculated an RMSE of 1092.87, suggesting that this model's predictions were off of the actual values by approx $1092.87

## Decision Tree: metrics on Testing data
I calculated an R2 score of 0.604 when my tree was set to a maximum (and best) depth of 5. This suggests that this model can explain approx %60.4 of our data in the prediction.
I calculated an RMSE of 1057.44, suggesting that this model's predictions were off of the actual values by approx $1057.44

- Please see "Sales Predictions 4", and "Sales Predictions 6" for full code and details

# Summary:
While neither model performed exceptionally well, the Decision Tree performed slightly better.
The best way to increase model performance, would be to add more data, and possibly another numerical category that correlates to sales.

### I will continue to add projects as I progress through my coding program. For comments/questions, you can reach my e-mail: jdjones1866@icloud.com
