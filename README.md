# CFG-Data-Group6
This is the collaborative work of Amy-Louise Snelling, Cherelle Brigden, Jemma John, Katrina Rogala, and Louise Wright. We have completed a data analysis to shed light on socio-economic benefits of access to internet across the world. 

## Implmenetation Guide
![Screenshot 2023-12-17 at 12 45 52 (2)](https://github.com/jemmaj24/CFG-Data-Group6/assets/31040598/95b2b4d0-df88-45ea-8320-1dc70440465a)

As shown in the diagram above the steps for implmeneting the code is as follows:
1. Download all the data files from the data.zip, unzip and store notebooks in the same folder as the data folder
2. Run the data cleaning and merging notebook: GroupProject_DataCleaning_12122023.ipynb (Note that there are 3 API calls in this notebook and each take upwards of 5 mins to fetch so give it time)
3. Once the data cleaning and merging notebook is run it will produce a csv with all the data merged, the default name is: internet_and_development_13122023.csv.
4. Begin exploring the various analysis notebooks which will pull data from internet_and_development_13122023.csv.

## Libraries which will be needed
Including but not limited to:
- pandas as pd
- matplotlib.pyplot as plt
- numpy as np
- seaborn as sns
- matplotlib.colors import ListedColormap
- plotly.express as px
- requests
- textwrap
- scipy import stats
- scipy.optimize import curve_fit
- sklearn.metrics import mean_squared_error, r2_score
- sklearn.model_selection import train_test_split
- sklearn.linear_model import LinearRegression
- sklearn.preprocessing import StandardScaler
- statsmodels.api as sm

## Datasets
Datasets in the data.zip folder:
- ddd_dataset.xslx - internet penetraion rates
- API_NY.GNP.PCAP.CD_DS2_en_csv_v2_5995153.csv - GNI per capita
- API_SI.POV.GINI_DS2_en_csv_v2_5994673.csv - GINI Index
- API_NY.GDP.PCAP.CD_DS2_en_csv_v2_5994720.csv - GDP per capita
- World Happiness Index by Reports 2013-2023 no nulls.csv - Happiness Index
- internet_price_2021.csv - Internet Prices
- idea_export_voter_turnout_database_world.xlsx - Voter Turnout
- any_name_to_wb_name.csv - matching country names to World Bank spelling of the names
- iso3_to_wb_name.csv - matching world bank country names to ISO codes

