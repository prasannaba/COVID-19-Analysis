# COVID-19-Analysis
COVID-19 analysis on data from CSSEGISandData covering all the 150+ countries in the data.

The output contains following tabs with graphs:  
1. Trends by country
	- Cases:
		- Cumulative
		- Daily
		- Seven day moving average
		- Recovered
		- Death
		- Active
	- Rate:
		- Recovery
		- Death
2. Trends comparison
	- Top 10 countries with option for log plot & selecting a countries on label
3. Top 10 bar graph
4. Worldwide bar graph

The source code uses bokeh, panel, holoviews & hvplot modules along with pandas.

The source code in Jupyter Notebook reads the following files from CSSEGISandData repository on Github:
	'https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv'
	'https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv'
	'https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv'

This Jupyter Notebook when executed generates standalone interactive HTML file (based on the option selected in the code at the end of the last but one cell) or generates interactive output in Jupyter Notebook.

This Notebook can be run online using mybinder.org, the requirements.txt file takes care of the dependencies required for mybinder.org

Check the output HTML file COVID19 dashboard-Date.html in 'output' folder for interactive standalone output.
	where 'Date' in the filename is in the format : Day, Month Date, YYYY. Example : 'Sunday, Aug 16, 2020'

Download HTML file on your system to see the graphs in tabs, Github has file size limitation.

Please check the type of images that are generated in the HTML file in 'Output' folder, placed for a quick glance.
