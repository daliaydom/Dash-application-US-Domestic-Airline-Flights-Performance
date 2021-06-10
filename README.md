# Data-Visualization-with-Python
## Final Addignment

In this Assignment, pandas, dash and ploty librearies were requiered to make a dashboard to monitor and report US domestic airline flights performance and yearly average flight delay statistics for a given year ( 2005 to 2020). 
Goal is to analyze the perfomance of the reporting airline to improve flight reliability thereby improving customer relaibility.

### Components of the report items:

1.  Yearly airline performance report

    For the chosen year provide,

    *   Number of flights under different cancellation categories using bar chart.
    *   Average flight time by reporting airline using line chart.
    *   Percentage of diverted airport landings per reporting airline using pie chart.
    *   Number of flights flying from each state using choropleth map.
    *   Number of flights flying to each state from each reporting airline using treemap chart.
    
2.  Yearly average flight delay statistics

    For the chosen year provide,

    *   Monthly average carrier delay by reporting airline for the given year.
    *   Monthly average weather delay by reporting airline for the given year.
    *   Monthly average natioanl air system delay by reporting airline for the given year.
    *   Monthly average security delay by reporting airline for the given year.
    *   Monthly average late aircraft delay by reporting airline for the given year.

### Requirements to create the dashboard

*   Create dropdown using the reference [here](https://dash.plotly.com/dash-core-components/dropdown?utm_medium=Exinfluencer\&utm_source=Exinfluencer\&utm_content=000026UJ\&utm_term=10006555\&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDV0101ENSkillsNetwork20297740-2021-01-01)
*   Create two HTML divisions that can accomodate two components (in one division) side by side. One is HTML heading and the other one is dropdown.
*   Add graph components.
*   Callback function to compute data, create graph and return to the layout.
