# covid-19-clusters-by-maryland-counties
## Background Information
The COVID-19 pandemic has resulted in a shortage of PPE, masks, and other sanitary supplies; there has also been a rush to bulk-buy soap, toilet paper, and hand sanitizer, among other things. The United States government has not handled the pandemic properly and the response to the virus has varied by state. I was interested in examining Maryland in particular to conduct a cluster analysis to determine which counties have higher rates of COVID-19 cases and confirmed deaths. By identifying this, I will then be sharing my work with my group mates to address an overarching question: How should Maryland allocate resources (PPE, financial, or otherwise) to the counties hit harder or the hardest by the virus? 

### Business Question 
Which counties have the most COVID-19 cases and deaths? 

## Data Sources
[Google Colaboratory](https://colab.research.google.com/drive/1VnqLR4BtRdX1dXCLZLtPD0CDTBK9WdTU?usp=sharing) shows the code that I wrote and used for this data analysis.

[MD_COVID-19 - Cases_by_County.csv](https://github.com/viv-sun/covid-19-clusters-by-maryland-counties/blob/main/MD_COVID-19_-_Cases_by_County.csv) shows the raw data for the number of cases by county on December 4, 2020 in Maryland. This raw data was downloaded from [the Maryland Open Data Portal](https://opendata.maryland.gov/Health-and-Human-Services/MD-COVID-19-Cases-by-County/tm86-dujs). 

[MD_COVID-19 - Confirmed_Deaths_by_County.csv](https://github.com/viv-sun/covid-19-clusters-by-maryland-counties/blob/main/MD_COVID-19_-_Confirmed_Deaths_by_County.csv) shows the raw data for the number of confirmed deaths by county on December 4, 2020 in Maryland. This raw data was downloaded from [the Maryland Open Data Portal](https://opendata.maryland.gov/Health-and-Human-Services/MD-COVID-19-Confirmed-Deaths-by-County/x28q-kc4a).

[MD COVID-19 - Dec 4 Cases and Deaths_Scatter Plot.csv](https://github.com/viv-sun/covid-19-clusters-by-maryland-counties/blob/main/MD%20COVID-19%20-%20Dec%204%20Cases%20and%20Deaths.xlsx) shows the compiled data (cases and deaths by county) for use in visualizing/creating a scatter plot.  

[MD COVID-19 - Dec 4 Cases and Deaths.xlsx](https://github.com/viv-sun/covid-19-clusters-by-maryland-counties/blob/main/MD%20COVID-19%20-%20Dec%204%20Cases%20and%20Deaths.xlsx) shows the cluster analysis conducted on the compiled raw data (cases and deaths by county). 

## Data Analysis/Metrics 
I used Python and Google Colaboratory to clean the raw data and compile it into one spreadsheet. I then created a scatter plot using Plotly Express to visualize the data. Finally, I exported the data to Excel to conduct a cluster analysis. 

### Graph for Baltimore Comparisons 
![alt text](https://github.com/viv-sun/covid-19-clusters-by-maryland-counties/blob/main/12-4%20scatter%20plot.jpg) 

This is the scatter plot for the raw data, created using Plotly Express in Google Colaboratory. 

## Summary
Just from looking at the scatter plot, it would be reasonable to assume that perhaps there could exist 2 or 3 potential cluster groups. I conducted a cluster analysis and found that all of the data points were sorted into one cluster, despite the fact that I had used three anchors. I tried it again with two anchors, but still yielded a similar cluster result in which all the data points were clustered into one group. 
