# 🏪 Carrera
Carrera : Superstore Time Series

## 🪟 Question
* Total Sales, Total Order, in Total, Yearly
* Most Use Ship Mode
* Most Valuable Customer
* New Customer Over 4 Years
* Customer Segmentation v Sales
* Most Valuable City, Region, State
* Product Category
* Best Model Combination (Arima / Seasonal Arima) ?

## 🚀 Output
### Total Order, Total Sales
* Total Sales is $ 261255.4107, Total Order is 4.922 Order
> ![image](https://github.com/user-attachments/assets/8dee5e53-f725-4b0d-8c54-dfc662a22196)
* in 2015 - 2018, Our Total Sales, Total Order Show Significant Improvement Over The Years

### Ship Mode
> ![image](https://github.com/user-attachments/assets/20cd6c17-9cdb-4b3c-88e8-d48c137e48f0)
* Most Use Shipping Mode is Standard Class, with 60 % of Total Order is Using Standard Class
* Our Favorite Ship Mode, Standard Class Average Time Trip is 4 - 5 Days

### Customer
> ![image](https://github.com/user-attachments/assets/32c0e57e-d67d-442e-a87d-5d3cc872e4d8)
* Our Top 5 Most Valuable Customer is Customer That Have Total Sales up to $ 25.000

> ![image](https://github.com/user-attachments/assets/bde447f3-71d2-4e54-a5bc-194167efc6dc)
* Contradictive With Our High Total Order, Our Sales is Bad at Gaining New Customer
* This Statement Show by Decreasing New Customer Over the Years, in 2018, Only 11 New Customer
* One Positive Good is, This is Show High Customer Retention on Our Sales Superstore

### Customer Segmentation
> ![image](https://github.com/user-attachments/assets/3cd612d3-62e8-43b9-88a1-9d0562a16cef)
* With 50 % of Our Total Sales Come From Consumer, This is Highlighting How Important in
* Maintain Customer Satisfaction and Product Availability
* Why Product Availability ? While Our Yearly New Customer is Bad, Maintain High Customer Retention is a High Priority
* Not Only for Consumer, Corporate, Home Office is Also Needed to Maintain High Customer Satisfaction
* More Customer Happy, More Suggestion to Our Sales, More New User, More Sales 👍

### Region
> ![image](https://github.com/user-attachments/assets/e384ee73-5a63-4546-9923-a62318f3d237)
> ![image](https://github.com/user-attachments/assets/10766025-ebed-4183-aa66-74cfc092b9dd)
> ![image](https://github.com/user-attachments/assets/42bd6ff7-57dc-4092-92d7-e7d2ef76bd83)
* While Highest Total Sales is West
* West isn't The Region With Highest Total State (East : 14) nor Highest Total City (Central : 181)
* Why West is on 1st Highest Total Sales ? High Total Order
* While Office Supplies Dominated all Regions, so Consumer Segment, Dominated all Regions

### State
> ![image](https://github.com/user-attachments/assets/cff3ef5f-f687-411d-8068-d410465f02c9)
* While California is in The West, New York, Texas, Washington is in East, Pennsylvania is in Central. California Remain The Highest Total Sales in all States
* California, New York is The Highest State in Their Each Respective Region 

### City
> ![image](https://github.com/user-attachments/assets/bd201d85-f01a-4081-9e3d-e0ac9bdc186c)
* Once Again, Our Top 2 is in East and West, Slightly Different From State Total Sales
* New York, Los Angeles is The Highest City in Their Each Respective Region

### Category
> ![image](https://github.com/user-attachments/assets/2b746651-9c2c-4dff-b4c8-6bdd1ca62f3b)
* Fantasticly, All of Our Product Category in Total Sales Distributed Around 30 %
* But, Office Supplies Dominate Total Order, Higher than Others
* While Technology Achieve 30 % ? High Average Total Sales, 27 % Higher than Office Supplies

> ![image](https://github.com/user-attachments/assets/7bb5f90d-d987-4f60-8685-cefc1a08b2ae)
* Phones, Chairs are Top Two of Highest Sub Category in Total Sales With Slightly Diff
* Follow by Storage, Tables, Binders

### Product
> ![image](https://github.com/user-attachments/assets/110e6813-fae0-4de5-8e51-e9d83e62e965)
> ![image](https://github.com/user-attachments/assets/7b6c0a85-c749-4d12-9672-ad1a7a3057a5)
> ![image](https://github.com/user-attachments/assets/cab39de9-7649-4654-9e04-a7bfa7e45c58)
> ![image](https://github.com/user-attachments/assets/b4388181-e705-46dc-b746-efbe005c3e52)
* While Technology Product sit on 1st, 3th, Office Supplies at 2nd, 5th, Furniture at 4th
* One Bold Statement is Average Technology Product is Expensive, Our Technology Product sit at 1st is Copier Machine
* Printer, Copier, VidCall Conference is Top 5 Product in Technology
* While in Office Supplies, Binding Machine is One of The Most Highest Product to Bought
* This is Supporting Statement in Sub Category, That Binders is One of The Most Highest Bought Product
* in Furniture, Chairs is Most Interesting Product in Furniture Section
* This is Supporting Statement in Sub Category, That Chairs is One of The Most Highest Bought Product

### Model
> ![image](https://github.com/user-attachments/assets/73b86c1d-09f4-439a-8bce-69b4e5b90cc6)
* Our Best Model is Seasonal Arima With (2, 0, 2) (1, 1, 0, 12)
* Why 0 Diff ? Our Daily Dataset is Already Stationer Through Multiple Test
* *p*, *q* at 2, This Result From PACF, ACF Plot

### 📄 Final
Our 4 Years in Store is Good, but, Several Challenges Occur for 2019
* Gaining Customer
* Maintain High Customer Satisfaction
* Maintain Stock Availability
* Increasing Total Sales in Low Total Sales City / State  

Store Owner / Management Must Tackle This Challenges in Order to Remain Sustain

While Consumer Segment is Responsible for 50 % Total Sales, Increasing Total Sales in Home Office + Corporate is Achievable by Making Contract to be Their Supplier (Maintain Long Term Income)

On Customer, Perform Several Customer Segmentation Method to Understand Customer Behaviour Even More to Personalized The Interaction, if this Store Have Apps, Performing Market Basket Analysis is Also Good to Recommend Other Product

in Order to Increase Total Sales, Increase Total Order and Maintain Customer Satisfaction. While Profit on This Store Can be Use to Develop the Store itself

Our Time Series Model is Perform Best With Seasonal Arima, Why ? There Are Seasonality in Daily Plot Data, While The Model itself Need More Effort to Improve, Our Model is Already at MVP Level.

### 🧨 More on [Notebook](Lab%2001.ipynb) And [Google Data Studio](https://lookerstudio.google.com/reporting/a29008d1-67a3-4fe4-a881-b00e612583c7)

### Others
* [Time Series Reference](https://www.linkedin.com/pulse/time-series-episode-1-how-select-correct-sarima-vasilis-kalyvas-jqcjf/)
* [Kaggle Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
