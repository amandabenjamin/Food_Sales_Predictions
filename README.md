# Food_Sales_Predictions
General: Applying knowledge of python / data science to predict the sales of various foods 

overview of the project, an explanation of the data (including visualizations), and a summary of the results and recommendations.

This project served as a means of practicing data science techniqus by means of helping a retailer understand the properties of products and outlets that play crucial roles in increasing sales. 

We were provided with a data set of various features (Item MRP (retail price), Item Types, Item Fat Content, Outlet size, ect.). 
We saw Item MRP has a postive correlation with Item OUlet Sales (below) 
![image](https://user-images.githubusercontent.com/99859350/161253668-12275026-6111-40cd-95bc-b96f619d426a.png)

and mid-sized oulets tend to have the higest item outlet sales (below)
![image](https://user-images.githubusercontent.com/99859350/161253839-2441be04-e465-4028-95f5-06eb34238118.png)

We compared the results of two machine learning techniques (linear regression and a simple regression tree) help predict item oulet sales from the given features (minus 'unique' features - as these would skew how the machine learned). Using the coefficient of determination (R^2) and RMSE error, we determined the predictive capabilies of the simple regression tree preformed best. 

Therefore, it is upon recommendation that if the investors wish to increase item outlet sales they should increase Item MRP and invest in more mid-sized outlets. 
