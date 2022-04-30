<!DOCTYPE html>
<html>

<head>
    <h1> Introduction to COVID-19 Epidemiology</h1>
</head>




<body>
<h2><strong> Map 1:
<h5 style = "display:inline-block"> <a href = "https://tribiab.github.io/CovidMaps/map1.html"> Covid 19 Incidence Rate per U.S County. </a></h5></h1></strong>

<img src = "/img/scmap1.png" alt = "Map 1">
<p>In this lab, I created two maps that would help visualize the epidemiology of the COVID-19 Pandemic. In the <strong> first </strong> map, I utilized this <a href = "https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv"> COVID-19 dataset </a> published by the New York Times. <br>
<p>The main functionality of this first map is for users to assess specific COVID-19 incidence rates across America. You'll notice that some of the incidence rates go over 100%, this is because the incidence rate is normalized per 1000 residents. Thus, if a county has over 100% incidence rate, it could mean that this county has a small population with high levels of transmission. Another alternative reason as to why the incidence rate could be so high is that some people may be reinfected.</p> Additionally, this map offers an interactive feature in which if you hover over a county-- you will be provided the incidence rate and the name of that specific county, and state, according to where you hover your mouse ( map.on('mousemove')). Thus, this map is a great resource to query for COVID-19 incidence rates with interactive functionality for more specific queries. </p><br>




<h2><strong> Map 2: 
<h5 style = "display:inline-block"> <a href = "https://tribiab.github.io/CovidMaps/map2.html"> Covid 19 Cases by County. </a></h5></h1>
<img src = "/img/scmap2.png" alt = "Map 2"> </strong>

<p> The <strong> second </strong> map was created by utilizing the <a href = "https://data.census.gov/cedsci/table?g=0100000US%24050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true"> 2018 ACS 5 year estimate</a> dataset.</p>

<p> The main functionality of this second map is for users to gain a general understanding of the distribution of COVID-19 cases. Unlike the first map where we normalized the incidence rates per 1000 residents; the second map visualizes the total count of COVID-19 cases per county. A critique of this map is that it can lead to wrong impressions. A user would notice that California has significantly higher cases of COVID-19 than essentially anywhere else. This is because the data has not been normalized, and that the reason as to why there are so many COVID cases in Los Angeles is because the population is very large, so naturally by connection there would be a higher count of COVID-19 cases. 
</body>
</html>