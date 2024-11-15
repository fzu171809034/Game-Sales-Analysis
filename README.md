# Game-Sales-Analysis
## 1. Introduction
Use exploratory data analysis (EDA) and machine learning models to conduct in-depth analysis of global game sales data, explore sales trends and user preferences across different platforms, genres, and regions, and visualize the data. Build and optimize forecasting models by analyzing features such as year, platform, and genre to predict sales in each region.
## 2. Tools used
1） python-data analysis

* pandas
 
* matplotlib
 
* seaborn
 
* sklearn
 
2） Tableau-data visualization

3） LinearRegression model; RandomForestRegressor model

## 3. Data collection and cleaning
### 3.1 Data collection
I got the dataset on kaggle. This dataset contains a list of video games with sales greater than 100,000 copies. It was generated by a scrape of vgchartz.com.

Fields include

Rank - Ranking of overall sales

Name - The games name

Platform - Platform of the games release (i.e. PC,PS4, etc.)

Year - Year of the game's release

Genre - Genre of the game

Publisher - Publisher of the game

NA_Sales - Sales in North America (in millions)

EU_Sales - Sales in Europe (in millions)

JP_Sales - Sales in Japan (in millions)

Other_Sales - Sales in the rest of the world (in millions)

Global_Sales - Total worldwide sales.

### 3.2 Data cleaning
1） Clean up some data item formats

2） Handle missing values

3） Group the data

## 4. Data visualization
1） Visualize the data by platform grouping to see which platform has higher sales in each region
![image](https://github.com/user-attachments/assets/511d52e8-f893-4834-a157-130c06386690)

2） Visualize the data by game type to see which game type is more popular in each region
![image](https://github.com/user-attachments/assets/504931e8-9815-466a-870c-7257c9bf277c)

3） Show sales trends in each region by year
![image](https://github.com/user-attachments/assets/909cd28f-4520-4e83-ab81-ec73b5e34e21)
![image](https://github.com/user-attachments/assets/5718ea2c-1a2f-4d02-bf4f-5ea90d39524b)

## 5. Prediction of Sales
The data were grouped for model training and testing. Linear regression and random forest models were used to predict sales, and Mean Squared Error and R2 Score were calculated for comparison.
