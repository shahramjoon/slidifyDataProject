---
title       : Births by five-year age group of mother, major area, region and country, 1950-2100
subtitle    : Worlds Population Prospect, United Nations
author      : shahramjoon
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, shiny, interactive]    # {mathjax, quiz, bootstrap}        
ext_widgets :  {rCharts: ["libraries/highcharts", "libraries/polycharts",libraries/nvd3", "libraries/morris"]} 
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Abstract
> * Data is provided from United Nation, Population Divsion  <a href="http//http://esa.un.org/wpp/Excel-Data/fertility.htm">click here to go to United Nations website</a>
> * Data presents number of Birth By 5 year age group of Mother between 1950-2010
> * Mother Age is categorized to 5 boundaries:    15-19 ,  20-24,     25-29,     30-34,    35-39,    40-44,    45-49
> * Data is from 199 countries , grouped to many different geograhical areas and continents, total of 36 areas, one is WORLD Population.   
> * Data covers births between 1950-2010, in 12 groups covering 5 years per group 
> * Application is using ShinyApp development framework.link to application <a href="https://shahramjoon.shinyapps.io/MyApp">here</a>
> * It provides a user interface that viewer can choose his/her own particular country or region from Drop Down. 
> * After user makes the choice, a plot is refresh on right side, presenting data related to user's chosen country or region. Plot is located on tab labeled "country/region" 
> * Supporting Data of Plot related to user's chosen country or region is refreshed on a tab lableled Table

--- 

##  Top Ten Most Powerful Countries in the World

Graph is showing number of Births based on Mother Age 


<div id = 'chart2c6c17062fd3' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart2c6c17062fd3()
    });
    function drawchart2c6c17062fd3(){  
      var opts = {
 "dom": "chart2c6c17062fd3",
"width":    800,
"height":    400,
"x": "agegroup",
"y": "total",
"group": "Area",
"type": "multiBarChart",
"id": "chart2c6c17062fd3" 
},
        data = [
 {
 "Area": "Brazil",
"agegroup": "g15_19",
"total": 29469 
},
{
 "Area": "Brazil",
"agegroup": "g20_24",
"total": 59794 
},
{
 "Area": "Brazil",
"agegroup": "g25_29",
"total": 52681 
},
{
 "Area": "Brazil",
"agegroup": "g30_34",
"total": 33967 
},
{
 "Area": "Brazil",
"agegroup": "g35_39",
"total": 19180 
},
{
 "Area": "Brazil",
"agegroup": "g40_44",
"total": 7425 
},
{
 "Area": "Brazil",
"agegroup": "g45_49",
"total": 1897 
},
{
 "Area": "China",
"agegroup": "g15_19",
"total": 69290 
},
{
 "Area": "China",
"agegroup": "g20_24",
"total": 504274 
},
{
 "Area": "China",
"agegroup": "g25_29",
"total": 428488 
},
{
 "Area": "China",
"agegroup": "g30_34",
"total": 214178 
},
{
 "Area": "China",
"agegroup": "g35_39",
"total": 109052 
},
{
 "Area": "China",
"agegroup": "g40_44",
"total": 43994 
},
{
 "Area": "China",
"agegroup": "g45_49",
"total": 5616 
},
{
 "Area": "France",
"agegroup": "g15_19",
"total": 2569 
},
{
 "Area": "France",
"agegroup": "g20_24",
"total": 13200 
},
{
 "Area": "France",
"agegroup": "g25_29",
"total": 16073 
},
{
 "Area": "France",
"agegroup": "g30_34",
"total": 10286 
},
{
 "Area": "France",
"agegroup": "g35_39",
"total": 4383 
},
{
 "Area": "France",
"agegroup": "g40_44",
"total": 1020 
},
{
 "Area": "France",
"agegroup": "g45_49",
"total": 59 
},
{
 "Area": "Germany",
"agegroup": "g15_19",
"total": 4169 
},
{
 "Area": "Germany",
"agegroup": "g20_24",
"total": 16246 
},
{
 "Area": "Germany",
"agegroup": "g25_29",
"total": 18217 
},
{
 "Area": "Germany",
"agegroup": "g30_34",
"total": 12001 
},
{
 "Area": "Germany",
"agegroup": "g35_39",
"total": 5103 
},
{
 "Area": "Germany",
"agegroup": "g40_44",
"total": 1122 
},
{
 "Area": "Germany",
"agegroup": "g45_49",
"total": 62 
},
{
 "Area": "India",
"agegroup": "g15_19",
"total": 205330 
},
{
 "Area": "India",
"agegroup": "g20_24",
"total": 462577 
},
{
 "Area": "India",
"agegroup": "g25_29",
"total": 356545 
},
{
 "Area": "India",
"agegroup": "g30_34",
"total": 209621 
},
{
 "Area": "India",
"agegroup": "g35_39",
"total": 107888 
},
{
 "Area": "India",
"agegroup": "g40_44",
"total": 41537 
},
{
 "Area": "India",
"agegroup": "g45_49",
"total": 10756 
},
{
 "Area": "Italy",
"agegroup": "g15_19",
"total": 1866 
},
{
 "Area": "Italy",
"agegroup": "g20_24",
"total": 9755 
},
{
 "Area": "Italy",
"agegroup": "g25_29",
"total": 13795 
},
{
 "Area": "Italy",
"agegroup": "g30_34",
"total": 10565 
},
{
 "Area": "Italy",
"agegroup": "g35_39",
"total": 5387 
},
{
 "Area": "Italy",
"agegroup": "g40_44",
"total": 1432 
},
{
 "Area": "Italy",
"agegroup": "g45_49",
"total": 91 
},
{
 "Area": "Japan",
"agegroup": "g15_19",
"total": 1195 
},
{
 "Area": "Japan",
"agegroup": "g20_24",
"total": 20002 
},
{
 "Area": "Japan",
"agegroup": "g25_29",
"total": 40725 
},
{
 "Area": "Japan",
"agegroup": "g30_34",
"total": 22253 
},
{
 "Area": "Japan",
"agegroup": "g35_39",
"total": 6503 
},
{
 "Area": "Japan",
"agegroup": "g40_44",
"total": 1054 
},
{
 "Area": "Japan",
"agegroup": "g45_49",
"total": 26 
},
{
 "Area": "Russian Federation",
"agegroup": "g15_19",
"total": 10839 
},
{
 "Area": "Russian Federation",
"agegroup": "g20_24",
"total": 45596 
},
{
 "Area": "Russian Federation",
"agegroup": "g25_29",
"total": 36888 
},
{
 "Area": "Russian Federation",
"agegroup": "g30_34",
"total": 20915 
},
{
 "Area": "Russian Federation",
"agegroup": "g35_39",
"total": 9290 
},
{
 "Area": "Russian Federation",
"agegroup": "g40_44",
"total": 2736 
},
{
 "Area": "Russian Federation",
"agegroup": "g45_49",
"total": 291 
},
{
 "Area": "United Kingdom",
"agegroup": "g15_19",
"total": 4072 
},
{
 "Area": "United Kingdom",
"agegroup": "g20_24",
"total": 11792 
},
{
 "Area": "United Kingdom",
"agegroup": "g25_29",
"total": 14673 
},
{
 "Area": "United Kingdom",
"agegroup": "g30_34",
"total": 10905 
},
{
 "Area": "United Kingdom",
"agegroup": "g35_39",
"total": 4650 
},
{
 "Area": "United Kingdom",
"agegroup": "g40_44",
"total": 934 
},
{
 "Area": "United Kingdom",
"agegroup": "g45_49",
"total": 26 
},
{
 "Area": "United States of America",
"agegroup": "g15_19",
"total": 31651 
},
{
 "Area": "United States of America",
"agegroup": "g20_24",
"total": 72201 
},
{
 "Area": "United States of America",
"agegroup": "g25_29",
"total": 66356 
},
{
 "Area": "United States of America",
"agegroup": "g30_34",
"total": 42942 
},
{
 "Area": "United States of America",
"agegroup": "g35_39",
"total": 18480 
},
{
 "Area": "United States of America",
"agegroup": "g40_44",
"total": 4004 
},
{
 "Area": "United States of America",
"agegroup": "g45_49",
"total": 218 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        chart
  .reduceXTicks(false)
          
        chart.xAxis
  .axisLabel("Mother Age Group")
  .staggerLabels(true)

        
        
        chart.yAxis
  .axisLabel("Birth(Thousands)")
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

---

##  Top Ten Most Powerful Countries in the World

Graph is showing number of Births based on Mother Age 



<div id = 'chart2c6c7f22776' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart2c6c7f22776()
    });
    function drawchart2c6c7f22776(){  
      var opts = {
 "dom": "chart2c6c7f22776",
"width":    800,
"height":    400,
"x": "Area",
"y": "total",
"group": "agegroup",
"type": "multiBarChart",
"id": "chart2c6c7f22776" 
},
        data = [
 {
 "Area": "Brazil",
"agegroup": "g15_19",
"total": 29469 
},
{
 "Area": "Brazil",
"agegroup": "g20_24",
"total": 59794 
},
{
 "Area": "Brazil",
"agegroup": "g25_29",
"total": 52681 
},
{
 "Area": "Brazil",
"agegroup": "g30_34",
"total": 33967 
},
{
 "Area": "Brazil",
"agegroup": "g35_39",
"total": 19180 
},
{
 "Area": "Brazil",
"agegroup": "g40_44",
"total": 7425 
},
{
 "Area": "Brazil",
"agegroup": "g45_49",
"total": 1897 
},
{
 "Area": "China",
"agegroup": "g15_19",
"total": 69290 
},
{
 "Area": "China",
"agegroup": "g20_24",
"total": 504274 
},
{
 "Area": "China",
"agegroup": "g25_29",
"total": 428488 
},
{
 "Area": "China",
"agegroup": "g30_34",
"total": 214178 
},
{
 "Area": "China",
"agegroup": "g35_39",
"total": 109052 
},
{
 "Area": "China",
"agegroup": "g40_44",
"total": 43994 
},
{
 "Area": "China",
"agegroup": "g45_49",
"total": 5616 
},
{
 "Area": "France",
"agegroup": "g15_19",
"total": 2569 
},
{
 "Area": "France",
"agegroup": "g20_24",
"total": 13200 
},
{
 "Area": "France",
"agegroup": "g25_29",
"total": 16073 
},
{
 "Area": "France",
"agegroup": "g30_34",
"total": 10286 
},
{
 "Area": "France",
"agegroup": "g35_39",
"total": 4383 
},
{
 "Area": "France",
"agegroup": "g40_44",
"total": 1020 
},
{
 "Area": "France",
"agegroup": "g45_49",
"total": 59 
},
{
 "Area": "Germany",
"agegroup": "g15_19",
"total": 4169 
},
{
 "Area": "Germany",
"agegroup": "g20_24",
"total": 16246 
},
{
 "Area": "Germany",
"agegroup": "g25_29",
"total": 18217 
},
{
 "Area": "Germany",
"agegroup": "g30_34",
"total": 12001 
},
{
 "Area": "Germany",
"agegroup": "g35_39",
"total": 5103 
},
{
 "Area": "Germany",
"agegroup": "g40_44",
"total": 1122 
},
{
 "Area": "Germany",
"agegroup": "g45_49",
"total": 62 
},
{
 "Area": "India",
"agegroup": "g15_19",
"total": 205330 
},
{
 "Area": "India",
"agegroup": "g20_24",
"total": 462577 
},
{
 "Area": "India",
"agegroup": "g25_29",
"total": 356545 
},
{
 "Area": "India",
"agegroup": "g30_34",
"total": 209621 
},
{
 "Area": "India",
"agegroup": "g35_39",
"total": 107888 
},
{
 "Area": "India",
"agegroup": "g40_44",
"total": 41537 
},
{
 "Area": "India",
"agegroup": "g45_49",
"total": 10756 
},
{
 "Area": "Italy",
"agegroup": "g15_19",
"total": 1866 
},
{
 "Area": "Italy",
"agegroup": "g20_24",
"total": 9755 
},
{
 "Area": "Italy",
"agegroup": "g25_29",
"total": 13795 
},
{
 "Area": "Italy",
"agegroup": "g30_34",
"total": 10565 
},
{
 "Area": "Italy",
"agegroup": "g35_39",
"total": 5387 
},
{
 "Area": "Italy",
"agegroup": "g40_44",
"total": 1432 
},
{
 "Area": "Italy",
"agegroup": "g45_49",
"total": 91 
},
{
 "Area": "Japan",
"agegroup": "g15_19",
"total": 1195 
},
{
 "Area": "Japan",
"agegroup": "g20_24",
"total": 20002 
},
{
 "Area": "Japan",
"agegroup": "g25_29",
"total": 40725 
},
{
 "Area": "Japan",
"agegroup": "g30_34",
"total": 22253 
},
{
 "Area": "Japan",
"agegroup": "g35_39",
"total": 6503 
},
{
 "Area": "Japan",
"agegroup": "g40_44",
"total": 1054 
},
{
 "Area": "Japan",
"agegroup": "g45_49",
"total": 26 
},
{
 "Area": "Russian Federation",
"agegroup": "g15_19",
"total": 10839 
},
{
 "Area": "Russian Federation",
"agegroup": "g20_24",
"total": 45596 
},
{
 "Area": "Russian Federation",
"agegroup": "g25_29",
"total": 36888 
},
{
 "Area": "Russian Federation",
"agegroup": "g30_34",
"total": 20915 
},
{
 "Area": "Russian Federation",
"agegroup": "g35_39",
"total": 9290 
},
{
 "Area": "Russian Federation",
"agegroup": "g40_44",
"total": 2736 
},
{
 "Area": "Russian Federation",
"agegroup": "g45_49",
"total": 291 
},
{
 "Area": "United Kingdom",
"agegroup": "g15_19",
"total": 4072 
},
{
 "Area": "United Kingdom",
"agegroup": "g20_24",
"total": 11792 
},
{
 "Area": "United Kingdom",
"agegroup": "g25_29",
"total": 14673 
},
{
 "Area": "United Kingdom",
"agegroup": "g30_34",
"total": 10905 
},
{
 "Area": "United Kingdom",
"agegroup": "g35_39",
"total": 4650 
},
{
 "Area": "United Kingdom",
"agegroup": "g40_44",
"total": 934 
},
{
 "Area": "United Kingdom",
"agegroup": "g45_49",
"total": 26 
},
{
 "Area": "United States of America",
"agegroup": "g15_19",
"total": 31651 
},
{
 "Area": "United States of America",
"agegroup": "g20_24",
"total": 72201 
},
{
 "Area": "United States of America",
"agegroup": "g25_29",
"total": 66356 
},
{
 "Area": "United States of America",
"agegroup": "g30_34",
"total": 42942 
},
{
 "Area": "United States of America",
"agegroup": "g35_39",
"total": 18480 
},
{
 "Area": "United States of America",
"agegroup": "g40_44",
"total": 4004 
},
{
 "Area": "United States of America",
"agegroup": "g45_49",
"total": 218 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        chart
  .reduceXTicks(false)
          
        chart.xAxis
  .axisLabel("Country")
  .staggerLabels(true)

        
        
        chart.yAxis
  .axisLabel("Birth(Thousands)")
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

---

##  Seven continents and WORLD

Graph is showing Total Number of Births between 1950-2010 


<div id = 'chart2c6c2a543eaa' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart2c6c2a543eaa()
    });
    function drawchart2c6c2a543eaa(){  
      var opts = {
 "dom": "chart2c6c2a543eaa",
"width":    800,
"height":    400,
"x": "Period",
"y": "total",
"group": "Area",
"type": "multiBarChart",
"id": "chart2c6c2a543eaa" 
},
        data = [
 {
 "Area": "AFRICA",
"Period": "1950-1955",
"total": 58084 
},
{
 "Area": "AFRICA",
"Period": "1955-1960",
"total": 64514 
},
{
 "Area": "AFRICA",
"Period": "1960-1965",
"total": 72031 
},
{
 "Area": "AFRICA",
"Period": "1965-1970",
"total": 79913 
},
{
 "Area": "AFRICA",
"Period": "1970-1975",
"total": 90001 
},
{
 "Area": "AFRICA",
"Period": "1975-1980",
"total": 101863 
},
{
 "Area": "AFRICA",
"Period": "1980-1985",
"total": 114268 
},
{
 "Area": "AFRICA",
"Period": "1985-1990",
"total": 125693 
},
{
 "Area": "AFRICA",
"Period": "1990-1995",
"total": 135867 
},
{
 "Area": "AFRICA",
"Period": "1995-2000",
"total": 147902 
},
{
 "Area": "AFRICA",
"Period": "2000-2005",
"total": 162066 
},
{
 "Area": "AFRICA",
"Period": "2005-2010",
"total": 178459 
},
{
 "Area": "ASIA",
"Period": "1950-1955",
"total": 307970 
},
{
 "Area": "ASIA",
"Period": "1955-1960",
"total": 319228 
},
{
 "Area": "ASIA",
"Period": "1960-1965",
"total": 355316 
},
{
 "Area": "ASIA",
"Period": "1965-1970",
"total": 380279 
},
{
 "Area": "ASIA",
"Period": "1970-1975",
"total": 387358 
},
{
 "Area": "ASIA",
"Period": "1975-1980",
"total": 372744 
},
{
 "Area": "ASIA",
"Period": "1980-1985",
"total": 400280 
},
{
 "Area": "ASIA",
"Period": "1985-1990",
"total": 438881 
},
{
 "Area": "ASIA",
"Period": "1990-1995",
"total": 410477 
},
{
 "Area": "ASIA",
"Period": "1995-2000",
"total": 377650 
},
{
 "Area": "ASIA",
"Period": "2000-2005",
"total": 369127 
},
{
 "Area": "ASIA",
"Period": "2005-2010",
"total": 374152 
},
{
 "Area": "Australia/New Zealand",
"Period": "1950-1955",
"total": 1257 
},
{
 "Area": "Australia/New Zealand",
"Period": "1955-1960",
"total": 1406 
},
{
 "Area": "Australia/New Zealand",
"Period": "1960-1965",
"total": 1482 
},
{
 "Area": "Australia/New Zealand",
"Period": "1965-1970",
"total": 1519 
},
{
 "Area": "Australia/New Zealand",
"Period": "1970-1975",
"total": 1590 
},
{
 "Area": "Australia/New Zealand",
"Period": "1975-1980",
"total": 1395 
},
{
 "Area": "Australia/New Zealand",
"Period": "1980-1985",
"total": 1437 
},
{
 "Area": "Australia/New Zealand",
"Period": "1985-1990",
"total": 1515 
},
{
 "Area": "Australia/New Zealand",
"Period": "1990-1995",
"total": 1588 
},
{
 "Area": "Australia/New Zealand",
"Period": "1995-2000",
"total": 1539 
},
{
 "Area": "Australia/New Zealand",
"Period": "2000-2005",
"total": 1548 
},
{
 "Area": "Australia/New Zealand",
"Period": "2005-2010",
"total": 1756 
},
{
 "Area": "Central America",
"Period": "1950-1955",
"total": 9980 
},
{
 "Area": "Central America",
"Period": "1955-1960",
"total": 11349 
},
{
 "Area": "Central America",
"Period": "1960-1965",
"total": 12728 
},
{
 "Area": "Central America",
"Period": "1965-1970",
"total": 14387 
},
{
 "Area": "Central America",
"Period": "1970-1975",
"total": 16170 
},
{
 "Area": "Central America",
"Period": "1975-1980",
"total": 16445 
},
{
 "Area": "Central America",
"Period": "1980-1985",
"total": 16504 
},
{
 "Area": "Central America",
"Period": "1985-1990",
"total": 16869 
},
{
 "Area": "Central America",
"Period": "1990-1995",
"total": 17671 
},
{
 "Area": "Central America",
"Period": "1995-2000",
"total": 17967 
},
{
 "Area": "Central America",
"Period": "2000-2005",
"total": 17519 
},
{
 "Area": "Central America",
"Period": "2005-2010",
"total": 17142 
},
{
 "Area": "EUROPE",
"Period": "1950-1955",
"total": 60559 
},
{
 "Area": "EUROPE",
"Period": "1955-1960",
"total": 61702 
},
{
 "Area": "EUROPE",
"Period": "1960-1965",
"total": 59061 
},
{
 "Area": "EUROPE",
"Period": "1965-1970",
"total": 54428 
},
{
 "Area": "EUROPE",
"Period": "1970-1975",
"total": 52141 
},
{
 "Area": "EUROPE",
"Period": "1975-1980",
"total": 50884 
},
{
 "Area": "EUROPE",
"Period": "1980-1985",
"total": 50370 
},
{
 "Area": "EUROPE",
"Period": "1985-1990",
"total": 49100 
},
{
 "Area": "EUROPE",
"Period": "1990-1995",
"total": 41857 
},
{
 "Area": "EUROPE",
"Period": "1995-2000",
"total": 37366 
},
{
 "Area": "EUROPE",
"Period": "2000-2005",
"total": 37021 
},
{
 "Area": "EUROPE",
"Period": "2005-2010",
"total": 39632 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1950-1955",
"total": 38363 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1955-1960",
"total": 43112 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1960-1965",
"total": 48498 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1965-1970",
"total": 51104 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1970-1975",
"total": 53937 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1975-1980",
"total": 56865 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1980-1985",
"total": 58922 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1985-1990",
"total": 59252 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1990-1995",
"total": 59221 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "1995-2000",
"total": 59684 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "2000-2005",
"total": 58710 
},
{
 "Area": "LATIN AMERICA AND THE CARIBBEAN",
"Period": "2005-2010",
"total": 56039 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1950-1955",
"total": 22074 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1955-1960",
"total": 24281 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1960-1965",
"total": 23834 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1965-1970",
"total": 20398 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1970-1975",
"total": 18533 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1975-1980",
"total": 18523 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1980-1985",
"total": 20175 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1985-1990",
"total": 21557 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1990-1995",
"total": 22382 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "1995-2000",
"total": 21697 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "2000-2005",
"total": 22332 
},
{
 "Area": "NORTHERN AMERICA",
"Period": "2005-2010",
"total": 23165 
},
{
 "Area": "WORLD",
"Period": "1950-1955",
"total": 488892 
},
{
 "Area": "WORLD",
"Period": "1955-1960",
"total": 514879 
},
{
 "Area": "WORLD",
"Period": "1960-1965",
"total": 560912 
},
{
 "Area": "WORLD",
"Period": "1965-1970",
"total": 588405 
},
{
 "Area": "WORLD",
"Period": "1970-1975",
"total": 604450 
},
{
 "Area": "WORLD",
"Period": "1975-1980",
"total": 603214 
},
{
 "Area": "WORLD",
"Period": "1980-1985",
"total": 646453 
},
{
 "Area": "WORLD",
"Period": "1985-1990",
"total": 697046 
},
{
 "Area": "WORLD",
"Period": "1990-1995",
"total": 672542 
},
{
 "Area": "WORLD",
"Period": "1995-2000",
"total": 647108 
},
{
 "Area": "WORLD",
"Period": "2000-2005",
"total": 652140 
},
{
 "Area": "WORLD",
"Period": "2005-2010",
"total": 674582 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        chart
  .reduceXTicks(false)
          
        chart.xAxis
  .axisLabel("Year Group")
  .staggerLabels(true)

        
        
        chart.yAxis
  .axisLabel("Birth(Thousands)")
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>
 
