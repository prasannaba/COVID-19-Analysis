# COVID-19 Analysis
COVID-19 analysis on data from **CSSEGISandData** covering all the 150+ countries in the data. This repository contains three source code files. <br>
1. **COVID-19_Analysis_v5_GH.ipynb** <br>
Trends by country, top 10 trends comparison, top 10 and worldwide bar graph. Standalone interactive HTML &/or deployment on web server(local host or cloud provider)
	
2. **COVID-19_Daily_Report_All_Regions_v2_JS.ipynb**<br>
Daily report bar graph for all countries: Confirmed, Recovered, Deaths, & Active. Incident Rate & Case Fatality Ratio in a table. Standalone interactive HTML &/or deployment on web server(local host or cloud provider)

3. **COVID-19_Daily_Report_All_Regions_v2.ipynb**<br>
Daily report bar graph for all countries: Confirmed, Recovered, Deaths, & Active. Incident Rate & Case Fatality Ratio in a table. Deployment on web server(local host or cloud provider)


## 1. COVID-19_Analysis_v5_GH.ipynb

The output from this source code contains following tabs with graphs:  
1. Trends by country
	- Cases:
		- Cumulative
		- Daily
		- Seven day moving average
		- Recovered
		- Death
		- Active
	- Rate & Ratio:
		- Incident Rate
		- Case Fatality Ratio
2. Trends comparison
	- Top 10 countries trends with options for log plot & highlight countries by clicking on countries label
3. Top 10 bar graph and table of data corresponding to graph
4. Worldwide bar graph and table of data corresponding to graph

The source code uses bokeh, panel, holoviews & hvplot modules along with pandas.

The source code in this Jupyter Notebook reads the following files from CSSEGISandData repository on Github:
	'https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv'
	'https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv'
	'https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv'

This Jupyter notebook when executed generates standalone interactive HTML file (based on the option selected in the code at the end of the last but one cell) and generates interactive output in Jupyter notebook. The standalone interactive HTML is created in 'output' folder, users can change the location & folder name in the code.

This can be deployed on a web server (local or cloud provider) using Bokeh server. On how to deploy, instructions are given in the notebook cells.

This notebook can be run online using mybinder.org, the requirements.txt file takes care of the dependencies required for mybinder.org

Check the output HTML file COVID19 dashboard-Date.html in 'output' folder for interactive standalone output.
	where 'Date' in the filename is in the format : Day, Month Date, YYYY. Example : 'Sunday, Aug 16, 2020'

## 2. COVID-19_Daily_Report_All_Regions_v2_JS.ipynb

The output from this source code contains: 

1. Daily graphs of Confirmed, Recovered, Deaths, & Active cases.
2. Daily Incident Rate & Case Fatality Ratio in a table.

The standalone interactive HTML is created in 'output' folder, users can change the location & folder name in the code.
This can be deployed on a web server (local or cloud provider) using Bokeh server. On how to deploy, instructions are given in the notebook cells.

## 3. COVID-19_Daily_Report_All_Regions_v2.ipynb

The output from this source code contains: 

1. Daily graphs of Confirmed, Recovered, Deaths, & Active cases.
2. Daily Incident Rate & Case Fatality Ratio in a table.

The interactive output is displayed in the notebook. This can be deployed on a web server (local or cloud provider) using Bokeh server. On how to deploy, instructions are given in the notebook cells.

**Note**:<br>
- The 'output' folder on this GitHub repository contains standalone interactive HTML files.<br> 
- GitHub has file size limitation (up to 5MB) so to view the file with size more than 5MB, you need to download that file(standalone interactive HTML) to your system & open it in a web browser.<br>
- Tested on Microsoft Edge, Google Chrome & Mozilla Firefox.<br>
- You can also check the type of graphs that are generated in the standalone interactive HTML files in the 'output' folder, placed for a quick glance.
