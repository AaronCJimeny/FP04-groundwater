# Connecting Wildfire Frequency, Drought Prevalence, and Groundwater Fluctuation in the Western United States.  
#### Name(s) and GitHub handles of team members: 
- Aaron Jimenez (@AaronCJimeny)
- Aiden Hamre (@Ahamre) 
- Thomas Ho (@thomasho123)
- Luke Mazza (LM2025)
#### Project Summary 
- This project compiled droubt data from the United States Droubt Monitor, wildfire data for the United States from the National Interagency Fire Center and for Colorado from the Department of Agriculture, and groundwater data from the USGS National Groundwater Monitoring Network. 
- Our inspiration for completing this project is that in the 21st century, there has been increasing attention in the United States directed toward these topics: droubt and water security in the Western States and wildfire risk, particularly in California
- We analyzed these datasets with respect to time, looking for correlations between droubt severity, wildfire frequency and severity, and groundwater levels. This project discusses trends in drought and wildfire for the United States, and trends in wildfire, drought, and groundwater level for the state of Colorado. 
#### Problem statement, question(s) and/or objective(s): 
1) Our primary objective is to analyze the connection between water level, drought, and wildfire in the United States. Datasets that we have explored extend back 20 years or more, so we have excellent long-form data with which to analyze these trends. 
2) Our research questions for this analysis include: How are waterlevels changing? Is there a correlation between the number or spread of wildfires in areas with low groundwater levels? How does drought severity affect groundwater fluctuation? Is there a clear connection between all three of these quanities?  
#### Datasets you will use (with links, if available): Data sets we will use inlcude data from  NOAA, USGS, BLR, National Agruclutrar Statistics Survey
-- From the USGS this dataset shows the depth to water level from the surface across various colorado counties. Using the parent website datasets for other states and counties can be found. https://cida.usgs.gov/ngwmn/index.jsp National Map view:https://cida.usgs.gov/ngwmn/index.jsp
-- Drought Monitor Datasets: https://droughtmonitor.unl.edu/DmData/DataDownload/ComprehensiveStatistics.aspx
-- Wildfire Datasets: https://catalog.data.gov/dataset/monitoring-trends-in-burn-severity-burned-area-boundaries-feature-layer-27201. https://catalog.data.gov/dataset/monitoring-trends-in-burn-severity-burned-area-boundaries-feature-layer-27201
#### Tools/packages you’ll use (with links): 
- [Matplotlib](https://github.com/matplotlib)
- [pandas](https://github.com/pandas-dev)
- [NumPy](https://github.com/numpy)
- [Python](https://github.com/python)
- [Sklearn](https://scikit-learn.org/stable/index.html)
#### Planned methodology/approach:
Approach:

 1)Why is monitoring Groundwater, wildfire, and drought important? (why care)
 
Answering this question provides context as to why people should care about our research/work. Groundwater is important because it is a critical component in agriculture in the US. It is also the main source of water for certain regions in the US like Castle Rock, CO and South Metro, CO [2]. Wildfire and drought have caused billions of dollars in damages to the American West, so it is crucial to track how they've changed, as well as how they correlate and connect to groundwater fluctuation.  

2)What reliable data exists to monitor groundwater?(Is there sufficient reliable data to analyze)

We need to collect data to analyze and see what patterns exist as well as to inform us more confidently on what affects and is affected by groundwater.

3)What is affected by Groundwater Fluctuations? (Identify problems that can be researched or worked on)

Answering this question allows us to ground our work and research into a specific focus, like how are wildfire frequency correlated to groundwater levels. This provides clarity on the purpose of our research and the problem we are trying to find a solution towards.

4)What can be gained from groundwater, drought, and wildfire monitoring? (How do we contribute to finding a solution to the problems we have identified)

Provides context again on the purpose of the research and clarifies the end goal of our research/work.

Methods:
- Github
- Anaconda/Python

#### Results:  
- Expected outcomes
    - We expect to find a strong pattern of declining water levels of groundwater in the United States. 
    - We expect that the decline in water levels in a region will correlate with an increased severity of wildfires/drought in the same timeframe. 
- Findings
    - At a national scale, droubt and wildfire were somewhat correlated in our data, but it was clear that more factors contribute to wildfire prevalance and severity.
    - For Colorado specifically, however, droubt severity and wildfire severity were very closely related.
    - For Colorado, there was no correlation between groundwater level and droubt severity or wildfire severity.
#### Member Contributions:
- Aaron Jimenez: Groundwater Analysis, final version of README
- Luke Mazza: Drought Analysis, 
- Thomas Ho: National Wildfire Analysis
- Aiden Hamre: Colorado Wildfire Analysis
#### References: 
1- https://droughtmonitor.unl.edu/CurrentMap.aspx

2- https://crgov.com/1792/Groundwater#:~:text=Castle%20Rock%2C%20and%20most%20South,Denver%2C%20Arapahoe%20and%20Laramie%20aquifers.

3- https://www.ncei.noaa.gov/access/monitoring/wildfires/ytd/0

4- https://frap.fire.ca.gov/mapping/gis-data/

5- https://catalog.data.gov/dataset/monitoring-trends-in-burn-severity-burned-area-boundaries-feature-layer-27201

6- https://waterdata.usgs.gov/nwis/uv/?referred_module=gw
