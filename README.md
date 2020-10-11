# Electronic-Sales-Analysis
Exploratory data analysis on electronic shop sales for 1 whole year  

## Background Information:

Sales analysis is examining sales reports to see what goods and services have and have not sold well. The analysis is used to determine how to stock inventory, how to measure the effectiveness of a sales force, how to set manufacturing capacity and to see how the company is performing against its goals.

In this repo we're doing sales analysis on the electronic shop for one entire year using python pandas, matplotlib, and seaborn to analyze and answer business question. the data contains hundred of thousands of electronic store purchase with this variable :

![image](https://user-images.githubusercontent.com/57277832/95669134-4c26fe80-0ba7-11eb-9d0a-360d764a7f47.png)

## Workflow : 
- Data cleaning :
  - Dropping Null values from the data frame
  - Dropping rows based on condition 
  - Changing the types of columns (astype, to_datetime, etc)

- Data Preparation :
  - Feature Engineering (adding columns to the table to get a better analysis)

- Analyze based on business questions

## Business questions :
- what was the best month for sales ? and how much was earned that month
- what city has the best total sales ?
- when is the best time to display an advertisement
- what product sold the most


## Conclusion / Summary : 
  - December is the best month of sales this might be affected due to Christmas holliday, the total sales of december itself is <b>4.6 million $</b> 
  
  - San Francisco California is the city with the highest number of sales with total sales more than <b>8 million $ </b>
  
  - There 2 best period to display advertisements the <b>morning period</b> and <b>evening period</b> 
    - for morning period the best time to display advertisements is during <b>9am - 12 pm </b> 
    - for evening period the best time to display advertisements is during <b>5pm - 7pm </b>
    
  - <b>Triple AAA battery</b> has the highest number of product sold while <b>LG Dryer</b> and <b>LG Washing Machine</b> has the lowest number of product sold
    - We also conclude that : 
      - 1. Product with lower prices has more quantity ordered compared with product with high prices 
      - 2. Personal electornic product (phone / laptop ) with higher prices tend to sell better compared to house appliance electronic


<details>
  <summary><b>Click to see the full analysis</b></summary>
<br>

# Analysis

### What was the best month for sales and how much was earned that month

![image](https://user-images.githubusercontent.com/57277832/95669331-f99b1180-0ba9-11eb-99b2-a8e2b0de6a37.png)

Based on the graph above we can clearly see that the best month of sales happened during December, this dataset is US dataset and the biggest US holiday happened during December (Chirstmas) so that might why sales in december is skyrocketing. The total sales during that month is somewhere around 4.6 million $

### What City Has the Best Total Sales

![image](https://user-images.githubusercontent.com/57277832/95669414-cc9b2e80-0baa-11eb-85c3-15cc27228bbb.png)

From our analysis we findout that San Francisco has the highest number of sales with more than 8 million $ total sales  while Portland Maine has the lowest total sales and becoming the only city with less than 1 million $ total of sales. This might be affected with number of population is various different city, and San Francisco widely known as the tech mecca of the world might have a factor in high total sales in that city 

### when is the best time to display an advertisement

![image](https://user-images.githubusercontent.com/57277832/95669555-58618a80-0bac-11eb-83e9-819dafc750fd.png)

We conclude there are 2 best period to display advertisement Morning Period and Evening Period
- <b>morning period </b>
  - the best time to display advertisement is during 9am - 12pm because of the number of transaction is steadily going up during that period 
  
- <b>Evening Period </b>
  - During evening period the best time to display advertisements is during 5pm to 7pm
  
- Note :
  - Any advertisement after 7pm is not recommended because of the number of transactions is steadily going down
  
### What product that sold the most 

![image](https://user-images.githubusercontent.com/57277832/95670048-3e767680-0bb1-11eb-8288-c3e33c82dfc4.png)

We are comparing the the number of quantity sold with the price of the each product, the green line show the average price of each product while the bars show the quantity sold for each product. 

From our data we conclude that :

1. product with lower prices has more quantity ordered compared with product with high prices 
2. personal electornic product (phone / laptop ) with higher prices tend to sell better compared to house appliance electronic

</details>


