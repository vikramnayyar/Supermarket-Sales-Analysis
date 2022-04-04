# Supermarket-Sales-Analysis

## Demo
The analysis is depicted in link: https://www.kaggle.com/code/vikram92/eda-for-all-dineout-restaurants-in-india-plotly#Question-#2:-How-are-average-ratings-distributed-across-India?

## Introduction
An analysis is done on https://www.dineout.co.in/. Thus, entire Indian Dineout restaurants are analyzed. Extracting several vital informations, more than **20** visualizations are very suitably plotted.     

The notebook evaluates regional performance and customer behaviour. 

## Dataset
The dataset comprises of actual information obtained from https://www.dineout.co.in/. This consists of diverse restaurants from **12** states and **22** major cities and numerous localities. 

The dataset was acquired using **web scraping** with BeautifulSoup. It has **7533** rows with **8** features.   

## Problem Statement
With smaller staff, capital and costing requirements, the restaurant business is on a consistent rise. Ratings, cuisines, cost and location all are vital to determine a restaurant's success. 

Nevertheless, awareness of these features is very challenging. Several online platforms provide restaurant reviews and ratings, but; various types of information like cuisine preferences, locality performance etc. remain unidentified. As; awareness of customer behaviour is essential, identifying a successful restaurant business becomes challenging. 

Therefore, a proper restaurant analysis is necessary to disclose the coverted insights of restaurant business. Thus, such a project is vital for restarant business. 

## Goal
This work was performed as a personal project. The motivation was to obtain exhaustive analysis of Indian restaurant business. Regional performance and customer behaviour of all Indian Dineout restaurants is obtained. About 9 types of comprehensive analysis are accomplished. 

## System Environment
![](https://forthebadge.com/images/badges/made-with-python.svg)



  [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width=200>](https://pandas.pydata.org/)     [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/512px-NumPy_logo_2020.svg.png" width=200>](https://numpy.org/)     [<img target="_blank" src="https://funthon.files.wordpress.com/2017/05/bs.png?w=772" width=200>](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)     [<img target="_blank" src="https://docs.python-requests.org/en/v1.1.0/_static/requests-sidebar.png" width=100>](https://docs.python-requests.org/en/latest/)     
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/37/Plotly-logo-01-square.png/1200px-Plotly-logo-01-square.png" width=200>](https://plotly.com/)     [<img target="_blank" src="https://miro.medium.com/max/1400/1*QxfkTc6W2v2jpQBo-HBw0g.jpeg" width=300>](https://plotly.com/dash/)                       


## Directory Structure

```bash
├── data                                           # Data files    
|  ├── all_restnt_details.json                     # Details of all restaurants (Web scraping output) 
|  ├── all_restnt_urls.csv                         # Links of all Dinoeut restaurants in India 
|  ├── clean_data.csv                              # Cleaned dataset 
|  ├── raw_set.csv                                 # Raw dataset (Web scraping output)
├── notebooks                                      # Main project files
|  ├── data_analysis.ipynb                         # Data analysis notebook
|  ├── web_scraping.ipynb                          # Web scraping notebook
├── visualizations                                 # Analysis visualizations
|  ├── 01-rating-distribution.png                  # Restaurant rating distribution 
|  ├── 02-cost-dstribution.png                     # Restaurant cost distribution
|  ├── 03-votes-distribution.png                   # Restaurant votes distribution
|  ├── 04-restnts-across-states.png                # Restaurant distribution across Indian states 
|  ├── 05-restnts-across-cities.png                # Restaurant distribution across Indian cities
|  ├── 06-rating-comparison-of-states.png          # Rating comparison of states
|  ├── 07-rating-comparison-of-cities.png          # Rating comparison of cities
|  ├── 08-cost-across-states.png                   # Restaurant cost distribution across states
|  ├── 09-cost-across-cities.png                   # Restaurant cost distribution across cities
|  ├── 10-votes-across-states.png                  # Restaurant votes distribution across states
|  ├── 11-votes-across-cities.png                  # Restaurant votes distribution across cities
|  ├── 12-comprehensive-comparison-of-states.png   # Performance comparison of all states   
|  ├── 13-top-cuisines-distribution.png            # Confusion matrix of XGBClassifier  
|  ├── 14-top-cuisines-comparison.png              # Top cuisines of respective states
|  ├── 15-favorite-cuisines-in-India.png           # Favourite cuisines in India
|  ├── 16-top-localities-Maharashtra.png           # Top localities in Maharashtra
|  ├── 17-top-localities-Delhi.png                 # Top localities in Delhi
|  ├── 18-top-localities-Karnataka.png             # Top localities in Karnataka
├── LICENSE                                        # License
├── README.md                                      # Repository description
├── requirements.txt                               # Required libraries

```

## Installing Dependencies
Foremost running the project, installing the dependencies is essential. 
* Ensure Python 3.8.8 or later is installed in the system. 
* All required libraries are listed in "requirements.txt". These are easily installed; by running the following command in project directory
```bash
pip install -r requirements.txt
```

## Run Project
The notebooks are provided in **notebooks** section. These run easily with Jupyter Notebook or Google Colab   
