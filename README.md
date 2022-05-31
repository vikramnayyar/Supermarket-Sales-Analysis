# Supermarket-Sales-Analysis

## Demo
The analysis is depicted in link: https://www.kaggle.com/code/vikram92/eda-for-supermarket-sales-memberships

## Introduction
An analysis is done on three supermarkets located at 'Mandalay', 'Naypyitaw' and 'Yangon' (Myanmar). Sales are analyzed in following ways
* Region wise sales
* Weekday-wise sales of members vs non-members
* Weekday-wise sales of males vs females
* Sales volume: members vs non-members
* Sales volume: males vs females
* Weekday-wise sales distribution: members vs non-members
* Weekday-wise sales distribution: males vs females 

Following product insights are obtained 
* most profitable items 
* item sales vs price 
* item ratings
* Product-wise sales distribution: members vs non-members
* Product-wise sales distribution: males vs females

Customer preferences are determined by following 
* Total customers vs memberships for males and females
* Sales by payment methods: members vs non-members
* Sales by payment methods: males vs females

Thus, a comprehensive analysis is obtained for the supermarket sales. 

## Dataset
The dataset was obtained from Kaggle (Link: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales). This consists of the historical sales of 3 different cities 'Mandalay', 'Naypyitaw' and 'Yangon' (Myanmar). 

## Problem Statement
Numerous economic events and global challenges impose pressure in pricing and increase competition. Besides, with maturing online market, future trading will acutely challenge prices. Furthermore, multi-channel sales and promotions demand supermarkets to capture broader market. Therefore, managing the supermarket business is very challenging and less rewarding.  

Regardless of the adverse situation, a supermarket is required to sustain the demands of a pool of customers. With this accomplishment; a supermarket easily maintains consistent sales.  

Therefore, a comprehensive supermarket analysis is vital to reveal the vital insights of supermarket business. 

## Goal
An acclaimed supermarket consistently attracts large customers. Therefore; an exhaustive analysis is performed, to improve sales, item selection and customer experience. Several aspects of sales, products and customer preferences are analyzed. The subsequent insights; aid to consistently attract a pool of customers, and thus; provide consistent revenues. 

## System Environment
![](https://forthebadge.com/images/badges/made-with-python.svg)



[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width=200>](https://pandas.pydata.org/)     [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/512px-NumPy_logo_2020.svg.png" width=200>](https://numpy.org/)     [<img target="_blank" src="https://matplotlib.org/_static/images/logo2.svg" width=200>](https://matplotlib.org/)     [<img target="_blank" src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width=300>](https://seaborn.pydata.org/)      [<img target="_blank" src="https://miro.medium.com/max/1300/1*2QUxAyr6J5hYCFgqh7j-dQ.png" width=200>](https://panel.holoviz.org/)     [<img target="_blank" src="https://holoviz.org/assets/hvplot.png" width=100>](https://hvplot.holoviz.org/)     [<img target="_blank" src="http://dev3lop.com/wp-content/uploads/2017/04/tableau-logo-tableau-software.jpg" width=400>](https://www.tableau.com/)                            


## Directory Structure

```bash
├── data                                           # Data files    
|  ├── data.csv                                    # Supermarket dataset 
├── notebooks                                      # Main project files
|  ├── dashboard.ipynb                             # Notebook for creating dashboard
|  ├── eda-for-supermarket.ipynb                   # Notebook for EDA
├── visualizations                                 # Analysis visualizations
|  ├── 01-monthly-sales.png                        # Monthly sales distribution od Supermarket
|  ├── 02-monthly-sales.png                        # Region-wise monthly sales
|  ├── 03-region-comparison.png                    # Performance comparison of regions
|  ├── 05-product-sales-vs-rating.png              # Product sales vs price vs margin
|  ├── 06-segment-wise-sales-.png                  # Sales comparison: members vs non-members & males vs females
|  ├── 07-daywise-sales.png                        # Weekday-wise Supermarket sales 
|  ├── 08-daywise-members-sale.png                 # Weekday-wise Supermarket sales: members vs non-members
|  ├── 09-daywise-gender-sales.png                 # Weekday-wise Supermarket sales: males vs females
|  ├── 10-category-wise-total-sales.png            # Sales contribution: members vs non-members & males vs females
|  ├── 11-product-wise-categorical-sales.png       # Product-wise sales contribution: members vs non-members & males vs females
|  ├── 12-payment-method-preferences.png           # Payment preferences: members vs non-members & males vs females
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
