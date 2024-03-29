## Berlin Airbnb Data (2015-2019)
The data was obtained from [Inside Airbnb](http://insideairbnb.com/get-the-data.html). 

The original datasets include listing information on Airbnb Berlin such as compiling dates, host names, host ids, latitudes and longitudes of the properties, dates of the last review, prices, room types, neighborhood groups, neighborhoods, minimum nights et cetera. The time range of the datasets is from November 2015 to July 2019.  

## Installation
> Anaconda 3

> Jupyter Notebook 6.0.0

> Python 3: 

>> NumPy, pandas, matplotlib, seaborn, datetime, sklearn.linear_model, sklearn.model_selection, sklearn.metrics, 

## Project Motivation

This project was created as one course project for the Data Scientist Nanodegree program from Udacity. Being generally interested in the German lodging market, I decided to analyze Berlin's Airbnb listing data in order to answer the following business questions:

> 1. Did the price increase in the last several years?
> 2. Is it more expensive to stay on the weekend?
> 3. Location, location, location? - What neighbourhood groups are the most expensive to stay in Berlin?
> 4. Predict the rental price.

## File Description
This repository contains two files, a README and a Jupyter Notebook file which contains the Python code for the data analysis and modeling.

## Results
Some key findings of this project:
#### 1. Lodging has become more expensive in Berlin in the last few years. Prices for shared rooms almost doubled from 2015 to 2019.

   ![Monthly prices and supply (number of hosts) of different room types in 2015–2019](https://miro.medium.com/max/732/1*cuzWzjpyeWfecm9jlQY7Zw.png)

   Fig 1. Monthly prices and supply (number of hosts) of different room types in 2015–2019.

#### 2. It seems to be cheaper to stay on the weekend, while Wednesdays and Thursdays appear to be more expensive than the other days of the week. Also, shared rooms are not necessarily cheaper than private rooms! However, it's important to note that the error bars suggest that the differences among the days are not always statistically significant.

   ![Prices of different room types on different days of the week](https://miro.medium.com/max/728/1*3ebb6qOiDvdSfidvlzgwzA.png)

   Fig 2. Prices of different room types on different days of the week

#### 3. Charlottenburg-Wilmersdorf, Mitte, and Pankow are among the most expensive districts on Airbnb Berlin, while Marzahn-Hellersdorf, Reinickendorf, and Steglitz-Zehlendorf are the cheapest. Overall, prices as well as supply vary drastically with different neighborhoods. Location Location Location!

   Table 1. Prices of different room types from different neighborhood groups in Berlin

   ![Prices of different room types from different neighborhood groups in Berlin](https://miro.medium.com/max/447/1*ibboAOAwQn-u8paf7pZTcg.jpeg)

## How to Contribute
Your help with making this project better is very welcome! To contribute, please feel free to make a pull request and start making the project a better one. 

And please make sure to write your commit messages to describe what the commit, when applied, does to the code.
## Acknowledgements
Special thanks goes to **[Inside Airbnb](http://insideairbnb.com/get-the-data.html)** for providing the data to make the world a better place!

