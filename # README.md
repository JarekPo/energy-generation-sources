# Analysis of Energy Generation Sources

##### Analysis of global data on energy generation sources, with a breakdown of production by energy source.

##### The ratio of forest cover to biomass generation.

##### An analysis of energy generation in Ireland.

---

This project analyzes global data on energy production sources, focusing on the breakdown of production by energy source. The historical data presented examines the relationship between bioenergy production (biomass) and afforestation in different countries, providing answers to specific questions in these areas. The project uses various libraries such as Pandas, Numpy, Matplotlib, Scikit-Learn, and Statsmodels to process, clean, and analyze the data.

## Data Sources

The primary data sources used include:

- Global_Energy.csv
- Electricity_Production_By_Source.csv
- Energy_From_Biomass.csv
- Forest_Coverage_Area.csv

## Data Analysis

The Global_Energy.csv data shows that biomass was the only energy source primarily used, followed by the introduction of coal in the mid-19th century. The 20th century saw the introduction of a range of energy sources, mainly fossil fuels. The analysis then filters the data to show 2019 as the most recent and complete year. The top fossil fuel-consuming economies from this analysis include electricity production from coal, oil, and gas, and electricity production from wind and solar sources.

The analysis focuses on wood as an energy source and answers what countries use it the most and which have the largest forest resources. Linear regression is used to predict electricity generation from biomass based on the area of forest cover.

The analysis then shifts to wind power generation in Ireland and looks at data from 2000-2020, which provides complete data for all power sources. An ARIMA model is used to forecast wind power generation for the comming years.

## Conclusion

The analysis leaves room for further research and analysis, including energy consumption and taking into account additional factors such as the number of inhabitants or geographical location. The project highlights the importance of renewable energy and highlights the ongoing shift towards these sources of energy.

## Data Sources

The data sources used in this project include:

- https://www.kaggle.com/code/gideonworks/renewable-energy-analysis
- https://www.kaggle.com/datasets/programmerrdai/renewable-energy
- https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy/downloads.html
- https://www.fao.org/faostat/en/#search/forest%20cover%20by%20country
- https://www.visualcapitalist.com/all-the-biomass-of-earth-in-one-graphic/
