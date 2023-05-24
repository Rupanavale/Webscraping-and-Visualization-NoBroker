# NoBroker-end-to-end-data-analysis-project
This repository contains data analysis project on NoBroker data, performed using python, power bi.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Visualization](#visualization)
- [Insights](#insights)
- [License](#license)

## Project Description
NoBroker is a disruptive real-estate platform that makes it possible to buy/sell/rent a house without paying any brokerage. NoBroker is a platform that removes this information asymmetry and provides a marketplace for free exchange of this information that used to cost 1-2 months of rent as brokerage.

In this project, I have webscrapped the NoBroker website using BeautifulSoup & performed exploratory data analysis using Power bi. The analysis includes data scraping, data exploration, data cleaning, data visualization, and deriving insights from the data.

The purpose of this project is to understand the data, discover patterns,trends, identify anomalies, and derive meaningful insights that can help to make informed decision or guide for further analysis.

## Installation
For web scraping you need to have python installed. 
If you don't have Python installed, you can download it from the official Python website: [(https://www.python.org/downloads/)] Or you can use Anaconda (Jupyter Notebook) : [https://www.anaconda.com/]
The following libraries are used in this project: 

 Pandas : [https://pandas.pydata.org/] 
 
 NumPy : [https://numpy.org/install/] 
 
 BeautifulSoup : [https://pypi.org/project/beautifulsoup4/]
 
 Time : [https://pypi.org/project/python-time/]
 
 Selenium : [https://www.selenium.dev/downloads/]
 
To run the Power BI Dashboard, follow these steps:

Install Power BI Desktop, which can be downloaded from the official Power BI website https://app.powerbi.com/

Clone or download this repository to your local machine.

git clone https://github.com/Rupanavale/NoBroker-end-to-end-data-analysis-project/edit/main/README.md

##  Usage
For Python:
1. Clone the repository to your local machine: git clone https://github.com/Rupanavale/NoBroker-end-to-end-data-analysis-project.git
2. Navigate to the specific dataset or analysis of interest.
3. Open the Python script or Jupyter notebook in your preferred environment (e.g., Jupyter Notebook, JupyterLab, or any Python IDE).
4. Execute the code cells or run the script to perform the EDA.
5. Explore the visualizations, summary statistics, and insights obtained from the analysis.

For Power BI:
1. Open Power BI Desktop.
2. Open the project by selecting the .pbix file from the downloaded repository.
3. Connect the dashboard to your dataset by importing the data or connecting to the data source.
4. Explore the different visualizations and interact with the dashboard to analyze the data.
5. Modify the dashboard as needed to suit your specific requirements and dataset.

## Data Source
The dataset used in this project is webscrapped using python.
The site which is scrapped is [https://www.nobroker.in/property/commercial/rent/pune/multiple?searchParam=W3sibGF0IjoxOC41NTc3NDQ2LCJsb24iOjczLjkxMjQ2NzQsInBsYWNlSWQiOiJDaElKaVNGeWVzWEF3anNScmN5RkZzUHlzTkUiLCJwbGFjZU5hbWUiOiJQdW5lIiwic2hvd01hcCI6ZmFsc2V9LHsibGF0IjoxOC42Mjk3ODExLCJsb24iOjczLjc5OTcwOTQsInBsYWNlSWQiOiJDaElKcy1xOWZ6ZTR3anNSLUtDbnNkcGxRaXciLCJwbGFjZU5hbWUiOiJQaW1wcmktQ2hpbmNod2FkIiwic2hvd01hcCI6ZmFsc2V9LHsibGF0IjoxOC41OTEyNzE2LCJsb24iOjczLjczODkwODk5OTk5OTk5LCJwbGFjZUlkIjoiQ2hJSjd4c0VTTUM3d2pzUjVkN0R3MXJyeWRBIiwicGxhY2VOYW1lIjoiSGluamF3YWRpIiwic2hvd01hcCI6ZmFsc2V9XQ==&radius=2.0&city=pune&locality=Pune,Pimpri-Chinchwad,Hinjawadi&commercialPropertyType=OFFICE_SPACE,COWORKING,SHOP,SHOWROOM,GODOWN_WAREHOUSE,INDUSTRIAL_SHED,INDUSTRIAL_BUILDING,OTHER_BUSINESS,RESTAURANT_OR_CAFE&orderBy=lastUpdateDate,desc]


## Technologies Used
- Microsoft Excel
- Python(Jupyter Notebook)
- Power BI

## Visualization
Link: https://github.com/Rupanavale/NoBroker-end-to-end-data-analysis-project/blob/main/NoBroker%20pb.pbix
![image](https://github.com/Rupanavale/NoBroker-end-to-end-data-analysis-project/assets/109949193/2028822e-4cfa-42dc-98a5-b19e7deef671)


## Insights
1. Showrooms as the category has the highest rents followed by restaurants & industrial sheds respectively.
2. 56.36% of properties are unfurnished which means more than half properties out of all are unfurnished.
3. Showrooms as the category has the highest deposits followed by restaurants & industrial sheds respectively.
4. The average rent per sqft is 47.71 Rs.



## License
This project is licensed under the [MIT License](LICENSE).
