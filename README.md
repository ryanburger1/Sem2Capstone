# Cosmetic Analysis

## Summary 
In this project I was charged with exploring what price causes the typical cosmetics consumer to remove a product from their cart and not buy it. In my analysis I was able to take my findings and come up with the ideal price point for any cosmetic company to not sell their product above. 

## Data Science Steps 

### Obtaining 
I obtained my data from kaggle and moved it into my repository. Below I have attached a link to the data set that you need to download in order to run the notebook:
- [eCommerce Data](https://www.kaggle.com/datasets/nowingkim/ecommerce-data-cosmetics-shop)

### Cleaning 
There was couple cleaning steps that needed to be taken before procceeding with the analysis. First, I made a seperate data frame with only the columns that I would need to run my analysis. Second, I removed any price's that were equal to zero since this would mean that they were not making a profit of the product sold. 

### Exploring 
I conducted a basic exploration to gain a better idea of what was in my data, which was helpful in conducting the rest of my analysis. 

### Modeling
Once I was done with the above steps I was able to start creating my machine learning models. I created an XGBoost model and a Logistic Regression model to help lead me towards my end goal 

### Interpreting 
After modeling my data I connected it back to the original business problem to come up with a recommendation. 

## Sources 

### Notebooks 
My final and draft notebook can both be found at the link below: 
- [ADD Notebooks LINK]()

### Presentation 
The presentation has an overview of the business problem, more information about the data, explanation of what I found in the data exploration, model evaluation and my final recommendation. 
- [ADD Presentation LINK]()

## Navagating Repository 
- Click [here INSERT LINK]() to be sent back to the home page of my repository. 
- Download the [dataset INSERT]() from kaggle to be able to run the code
- Go to the notebooks folder and you will find both draft and [Final Notebooks INSERT LINK]()

## Libraries 
Below I have complied a list of the different libraries I used in my code: 
- Pandas 
- Matplotlib 
- Squarify 
- Sklearn
- XGBoost 
- Logistic Regression 

### Recommendations 
During my analysis my goal was the find what dollar amount was causes more customers to remove data from there cart then purchase the item. I was able to concluded at $INSERT the amount of customers more customers started to remove items from their cart. 

My two reccomendations for cosmetics companies are: 
- Price less items above $INSERT AMOUNT 
- Have less of the higher priced items in your inventory at one time 
- Look into having a sale on the higher priced items that you currently have that are not selling
