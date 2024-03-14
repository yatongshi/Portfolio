# Kaggle Exploratory for TVX Product Data
### Here is a link to the full project code and repository: <a href="https://github.com/yatongshi/Kaggle-Exploratory-for-TVX-product-data/tree/main"> Kaggle Exploratory for TVX Product Data </a>

_Main Directive: My goal is to look through the list of repaired components for cleaning machine and uncover and analyze the components that cost the most._

* Using Python to conduct exploratory data analysis on 131 maiteinance data
* Utilizing these results, I was able to create a in total $20000 saving in the long run by replacing the easily broken components. <br />


## 1. Which Components are Outliers Within the Context of Sum Price and Quantity?

   ![Portfolio](images/outliers.png) 

Comment: we can see that there are 5 components that are way higher than the average sum price and 8 components that have broken more than 15 times.

## 2. Which Components Cost the Most Money?

 ![Portfolio](images/most_money.png) 
 
Comment: From seeing the distribution of the top 20 components that have the highest sum cost, we can see that the top 5 components have the highest sum price that are much more than the rest of replaced components.
List: 驱动电机-24V-800W 1234.00前车轮4467.26 操控面板-3.5寸-DALA
3781.80污水箱-130L-绿色3271.29 吸水电机组件-24V-500W-T130 $3155.46

## 3. Which Components are More Likely to be Broken?

   ![Portfolio](images/broken.png) 
 

Comment: we can see that there is a distinct difference between the components that have been replaced more than 10 times where the unit might be more likely to break again in the future.

## 4. Is there a Seasonal or Monthly Pattern In the Broken Components Data?

 ![Portfolio](images/seasonal.png) 

Comment: The number fluctuates within the two monthes from October to December where there is a short spike around November 15th. It could be because of the quick temerature drop around first frost around the region. It's worth to investigave further once we obtained more data points over the month.

_In Summary:_
* In analyzing the data, it's evident that certain components stand out for their frequent replacements and high costs. The top 5 components, notably the 驱动电机-24V-800W, 前车轮, 操控面板-3.5寸-DALA, 污水箱-130L-绿色, and 吸水电机组件-24V-500W-T130, exhibit significantly higher costs compared to others. Moreover, with 8 components breaking more than 15 times, it highlights potential areas for improvement in components' durability and reliability. The fluctuations observed, particularly around November 15th, may suggest external factors like temperature drops impacting component performance, which worth investigating further.

* Suggestions: To mitigate future breakdowns and reduce maintenance costs, it's imperative for the company to focus on several key areas. Firstly, conducting a thorough investigation into the components prone to frequent replacements, especially those surpassing the 10-time mark, will provide valuable insights into potential design or manufacturing issues. Additionally, establishing a monitoring system to track environmental factors like temperature fluctuations can aid in predicting and preventing breakdowns caused by external conditions. Lastly, ongoing data collection and analysis are essential to continuously refine strategies and address emerging trends, ensuring sustained product performance and customer satisfaction.


