# Analyzing wildfire activities in Australia


## Introduction
This project focuses on exploring and analysing wildfire activities in Australia. Used visualization libraries such as Matplotlib, Pandas, Seaborn and Folium to create informative plots and charts.

### 💻 Tools and Technologies:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) 
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23F7EBE2?style=for-the-badge&logo=pandas&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![JupyterNotebook](https://img.shields.io/badge/JupyterNotebook-FACCA7?style=for-the-badge&logo=Jupyter)
![GIT](https://img.shields.io/badge/Git-fc6d26?style=for-the-badge&logo=git&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-86B4AD?style=for-the-badge)

## Dataset
**Historical Wildfires**

This wildfire dataset contains data on fire activities in Australia starting from 2005. Additional information can be found [here](https://earthdata.nasa.gov/earth-observation-data/near-real-time/firms/c6-mcd14dl).

Variables

- Region: the 7 regions
- Date: in UTC and provide the data for 24 hours ahead
- Estimated_fire_area: daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% for a each region in km2
- Mean_estimated_fire_brightness: daily mean (by flagged fire pixels(=count)) of estimated fire brightness for presumed vegetation fires with a confidence level > 75% in Kelvin
- Mean_estimated_fire_radiative_power: daily mean of estimated radiative power for presumed vegetation fires with a confidence level > 75% for a given region in megawatts
- Mean_confidence: daily mean of confidence for presumed vegetation fires with a confidence level > 75%
- Std_confidence: standard deviation of estimated fire radiative power in megawatts
- Var_confidence: Variance of estimated fire radiative power in megawatts
- Count: daily numbers of pixels for presumed vegetation fires with a confidence level of larger than 75% for a given region
- Replaced: Indicates with an Y whether the data has been replaced with standard quality data when they are available (usually with a 2-3 month lag). Replaced data has a slightly higher quality in terms of locations

## Some Visualization Outputs

* This plot represents that the estimated fire area was on its peak after 2011, April and before 2012. You can verify on google/news, this was the time of maximum wildfire hit in Austrailia.![image](https://github.com/my3amarnath/Analyzing-wildfire-activities-in-Australia/assets/39696237/3d9aa834-cf96-4fac-a994-a7e44e08aa4f)
* Percentage of Pixels for Presumed Vegetation Fires by Region ![image](https://github.com/my3amarnath/Analyzing-wildfire-activities-in-Australia/assets/39696237/9e192f68-7330-4e42-8561-3273fba7e168)
* Histogram of Mean Estimated Fire Brightness ![image](https://github.com/my3amarnath/Analyzing-wildfire-activities-in-Australia/assets/39696237/053448d8-0134-4547-b270-7bdd99ece0e8)![image](https://github.com/my3amarnath/Analyzing-wildfire-activities-in-Australia/assets/39696237/ab7ca162-760d-4b73-9e86-52fa9a3175bf)
* Correlation between mean estimated fire radiative power and mean confidence level ![image](https://github.com/my3amarnath/Analyzing-wildfire-activities-in-Australia/assets/39696237/15679ea5-1065-4dfa-9e7c-418b573a6f5b)
* Seven wildfire regions of Australia using Folium ![image](https://github.com/my3amarnath/Analyzing-wildfire-activities-in-Australia/assets/39696237/7558863f-f674-45f6-8717-03bd2724dd5c) ![image](https://github.com/my3amarnath/Analyzing-wildfire-activities-in-Australia/assets/39696237/cc0b87a4-79d9-4a9e-9727-a423cdcd3877)








