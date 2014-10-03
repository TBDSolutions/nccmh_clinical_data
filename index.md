---
title       : Uses of Data
subtitle    : in Clinical Quality Measurement
author      : Joshua Hagedorn
job         : tbd
#logo        : tbd-icon-small.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : zenburn       #      
widgets     : []            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: libraries/nvd3}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---



## Context: Resources
(- $) (+ #) -> (- Redundancy) (+ Value %)

>- Less money
>- More people
>- Reduce redundancy
>- Increase value

--- .class #id 

## Context: Costs in MSHN Region


<div id = 'chart31005322f0c' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart31005322f0c()
    });
    function drawchart31005322f0c(){  
      var opts = {
 "dom": "chart31005322f0c",
"width":    800,
"height":    400,
"x": "FY",
"y": "CostInMillions",
"group": "ServiceType",
"type": "stackedAreaChart",
"id": "chart31005322f0c" 
},
        data = [
 {
 "X": 1,
"FY": 2006,
"ServiceType": "Care Coordination",
"CostInMillions":      42.613862,
"Cost1kSvd":     5353500.25 
},
{
 "X": 2,
"FY": 2006,
"ServiceType": "Crisis and Respite",
"CostInMillions":       6.931051,
"Cost1kSvd":      870735.05 
},
{
 "X": 3,
"FY": 2006,
"ServiceType": "Employment Services",
"CostInMillions":      30.669278,
"Cost1kSvd":     3852924.37 
},
{
 "X": 4,
"FY": 2006,
"ServiceType": "Equipment",
"CostInMillions":       1.036978,
"Cost1kSvd":      130273.62 
},
{
 "X": 5,
"FY": 2006,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     130.055799,
"Cost1kSvd":    16338668.22 
},
{
 "X": 6,
"FY": 2006,
"ServiceType": "Hospital-based Services",
"CostInMillions":      30.287516,
"Cost1kSvd":     3804964.32 
},
{
 "X": 7,
"FY": 2006,
"ServiceType": "Medication",
"CostInMillions":        9.74048,
"Cost1kSvd":     1223678.39 
},
{
 "X": 8,
"FY": 2006,
"ServiceType": "Other",
"CostInMillions":       1.247035,
"Cost1kSvd":      156662.69 
},
{
 "X": 9,
"FY": 2006,
"ServiceType": "Outpatient Treatment",
"CostInMillions":      12.323178,
"Cost1kSvd":     1548137.94 
},
{
 "X": 10,
"FY": 2006,
"ServiceType": "Physical Health Services",
"CostInMillions":       8.868717,
"Cost1kSvd":     1114160.43 
},
{
 "X": 11,
"FY": 2006,
"ServiceType": "Screening & Assessment",
"CostInMillions":       9.032421,
"Cost1kSvd":     1134726.26 
},
{
 "X": 12,
"FY": 2006,
"ServiceType": "Transportation",
"CostInMillions":       2.321038,
"Cost1kSvd":      291587.69 
},
{
 "X": 13,
"FY": 2007,
"ServiceType": "Care Coordination",
"CostInMillions":       46.87062,
"Cost1kSvd":     5973062.32 
},
{
 "X": 14,
"FY": 2007,
"ServiceType": "Crisis and Respite",
"CostInMillions":       8.850937,
"Cost1kSvd":     1127938.96 
},
{
 "X": 15,
"FY": 2007,
"ServiceType": "Employment Services",
"CostInMillions":      31.269296,
"Cost1kSvd":     3984872.69 
},
{
 "X": 16,
"FY": 2007,
"ServiceType": "Equipment",
"CostInMillions":       0.391234,
"Cost1kSvd":       49857.78 
},
{
 "X": 17,
"FY": 2007,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     138.880188,
"Cost1kSvd":    17698507.46 
},
{
 "X": 18,
"FY": 2007,
"ServiceType": "Hospital-based Services",
"CostInMillions":      27.125668,
"Cost1kSvd":     3456820.19 
},
{
 "X": 19,
"FY": 2007,
"ServiceType": "Medication",
"CostInMillions":       8.595706,
"Cost1kSvd":     1095413.02 
},
{
 "X": 20,
"FY": 2007,
"ServiceType": "Other",
"CostInMillions":       2.871638,
"Cost1kSvd":      365953.61 
},
{
 "X": 21,
"FY": 2007,
"ServiceType": "Outpatient Treatment",
"CostInMillions":      11.864475,
"Cost1kSvd":     1511975.91 
},
{
 "X": 22,
"FY": 2007,
"ServiceType": "Physical Health Services",
"CostInMillions":       8.589161,
"Cost1kSvd":     1094578.95 
},
{
 "X": 23,
"FY": 2007,
"ServiceType": "Screening & Assessment",
"CostInMillions":       9.531487,
"Cost1kSvd":     1214666.37 
},
{
 "X": 24,
"FY": 2007,
"ServiceType": "Transportation",
"CostInMillions":       1.056393,
"Cost1kSvd":      134623.81 
},
{
 "X": 25,
"FY": 2008,
"ServiceType": "Care Coordination",
"CostInMillions":      49.248123,
"Cost1kSvd":     6379290.54 
},
{
 "X": 26,
"FY": 2008,
"ServiceType": "Crisis and Respite",
"CostInMillions":       7.590687,
"Cost1kSvd":      983249.61 
},
{
 "X": 27,
"FY": 2008,
"ServiceType": "Employment Services",
"CostInMillions":      39.490188,
"Cost1kSvd":     5115309.33 
},
{
 "X": 28,
"FY": 2008,
"ServiceType": "Equipment",
"CostInMillions":       0.940484,
"Cost1kSvd":      121824.35 
},
{
 "X": 29,
"FY": 2008,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     137.356028,
"Cost1kSvd":    17792231.61 
},
{
 "X": 30,
"FY": 2008,
"ServiceType": "Hospital-based Services",
"CostInMillions":      27.022979,
"Cost1kSvd":     3500385.88 
},
{
 "X": 31,
"FY": 2008,
"ServiceType": "Medication",
"CostInMillions":       8.679773,
"Cost1kSvd":     1124322.93 
},
{
 "X": 32,
"FY": 2008,
"ServiceType": "Other",
"CostInMillions":       0.392004,
"Cost1kSvd":       50777.72 
},
{
 "X": 33,
"FY": 2008,
"ServiceType": "Outpatient Treatment",
"CostInMillions":      12.003843,
"Cost1kSvd":     1554901.94 
},
{
 "X": 34,
"FY": 2008,
"ServiceType": "Physical Health Services",
"CostInMillions":       9.953256,
"Cost1kSvd":     1289281.87 
},
{
 "X": 35,
"FY": 2008,
"ServiceType": "Screening & Assessment",
"CostInMillions":       9.333895,
"Cost1kSvd":     1209053.76 
},
{
 "X": 36,
"FY": 2008,
"ServiceType": "Transportation",
"CostInMillions":       2.241453,
"Cost1kSvd":      290343.65 
},
{
 "X": 37,
"FY": 2009,
"ServiceType": "Care Coordination",
"CostInMillions":      49.210999,
"Cost1kSvd":     6149837.42 
},
{
 "X": 38,
"FY": 2009,
"ServiceType": "Crisis and Respite",
"CostInMillions":       8.149038,
"Cost1kSvd":     1018375.16 
},
{
 "X": 39,
"FY": 2009,
"ServiceType": "Employment Services",
"CostInMillions":      30.183907,
"Cost1kSvd":     3772045.36 
},
{
 "X": 40,
"FY": 2009,
"ServiceType": "Equipment",
"CostInMillions":       1.083057,
"Cost1kSvd":      135348.29 
},
{
 "X": 41,
"FY": 2009,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     156.685168,
"Cost1kSvd":    19580750.81 
},
{
 "X": 42,
"FY": 2009,
"ServiceType": "Hospital-based Services",
"CostInMillions":      27.384664,
"Cost1kSvd":     3422227.44 
},
{
 "X": 43,
"FY": 2009,
"ServiceType": "Medication",
"CostInMillions":       9.961766,
"Cost1kSvd":     1244909.52 
},
{
 "X": 44,
"FY": 2009,
"ServiceType": "Other",
"CostInMillions":       0.554721,
"Cost1kSvd":       69322.79 
},
{
 "X": 45,
"FY": 2009,
"ServiceType": "Outpatient Treatment",
"CostInMillions":      13.971857,
"Cost1kSvd":     1746045.61 
},
{
 "X": 46,
"FY": 2009,
"ServiceType": "Physical Health Services",
"CostInMillions":       8.846238,
"Cost1kSvd":     1105503.37 
},
{
 "X": 47,
"FY": 2009,
"ServiceType": "Screening & Assessment",
"CostInMillions":       9.576346,
"Cost1kSvd":     1196744.06 
},
{
 "X": 48,
"FY": 2009,
"ServiceType": "Transportation",
"CostInMillions":       1.727071,
"Cost1kSvd":      215829.92 
},
{
 "X": 49,
"FY": 2010,
"ServiceType": "Care Coordination",
"CostInMillions":      50.757631,
"Cost1kSvd":      6373384.1 
},
{
 "X": 50,
"FY": 2010,
"ServiceType": "Crisis and Respite",
"CostInMillions":       8.088793,
"Cost1kSvd":     1015669.64 
},
{
 "X": 51,
"FY": 2010,
"ServiceType": "Employment Services",
"CostInMillions":       32.54015,
"Cost1kSvd":     4085905.32 
},
{
 "X": 52,
"FY": 2010,
"ServiceType": "Equipment",
"CostInMillions":       1.126856,
"Cost1kSvd":      141493.72 
},
{
 "X": 53,
"FY": 2010,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     157.385646,
"Cost1kSvd":    19762135.36 
},
{
 "X": 54,
"FY": 2010,
"ServiceType": "Hospital-based Services",
"CostInMillions":      27.136653,
"Cost1kSvd":     3407414.99 
},
{
 "X": 55,
"FY": 2010,
"ServiceType": "Medication",
"CostInMillions":      11.888229,
"Cost1kSvd":     1492745.98 
},
{
 "X": 56,
"FY": 2010,
"ServiceType": "Other",
"CostInMillions":       0.606968,
"Cost1kSvd":       76213.96 
},
{
 "X": 57,
"FY": 2010,
"ServiceType": "Outpatient Treatment",
"CostInMillions":       15.84638,
"Cost1kSvd":     1989751.38 
},
{
 "X": 58,
"FY": 2010,
"ServiceType": "Physical Health Services",
"CostInMillions":      14.702819,
"Cost1kSvd":      1846160.1 
},
{
 "X": 59,
"FY": 2010,
"ServiceType": "Screening & Assessment",
"CostInMillions":       9.660163,
"Cost1kSvd":     1212978.78 
},
{
 "X": 60,
"FY": 2010,
"ServiceType": "Transportation",
"CostInMillions":       1.203583,
"Cost1kSvd":      151127.95 
},
{
 "X": 61,
"FY": 2011,
"ServiceType": "Care Coordination",
"CostInMillions":      54.888127,
"Cost1kSvd":     6934697.03 
},
{
 "X": 62,
"FY": 2011,
"ServiceType": "Crisis and Respite",
"CostInMillions":       7.403879,
"Cost1kSvd":      935423.75 
},
{
 "X": 63,
"FY": 2011,
"ServiceType": "Employment Services",
"CostInMillions":      37.750589,
"Cost1kSvd":     4769499.56 
},
{
 "X": 64,
"FY": 2011,
"ServiceType": "Equipment",
"CostInMillions":       1.054661,
"Cost1kSvd":      133248.39 
},
{
 "X": 65,
"FY": 2011,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     175.185575,
"Cost1kSvd":    22133363.87 
},
{
 "X": 66,
"FY": 2011,
"ServiceType": "Hospital-based Services",
"CostInMillions":      30.128484,
"Cost1kSvd":     3806504.61 
},
{
 "X": 67,
"FY": 2011,
"ServiceType": "Medication",
"CostInMillions":      12.005911,
"Cost1kSvd":     1516855.46 
},
{
 "X": 68,
"FY": 2011,
"ServiceType": "Other",
"CostInMillions":       0.286611,
"Cost1kSvd":       48993.33 
},
{
 "X": 69,
"FY": 2011,
"ServiceType": "Outpatient Treatment",
"CostInMillions":      16.445063,
"Cost1kSvd":     2077708.53 
},
{
 "X": 70,
"FY": 2011,
"ServiceType": "Physical Health Services",
"CostInMillions":      13.057021,
"Cost1kSvd":     1649655.21 
},
{
 "X": 71,
"FY": 2011,
"ServiceType": "Screening & Assessment",
"CostInMillions":       9.860682,
"Cost1kSvd":     1245822.11 
},
{
 "X": 72,
"FY": 2011,
"ServiceType": "Transportation",
"CostInMillions":       1.484749,
"Cost1kSvd":      187586.73 
},
{
 "X": 73,
"FY": 2012,
"ServiceType": "Care Coordination",
"CostInMillions":      60.340533,
"Cost1kSvd":     7605310.44 
},
{
 "X": 74,
"FY": 2012,
"ServiceType": "Crisis and Respite",
"CostInMillions":       7.637112,
"Cost1kSvd":      962580.29 
},
{
 "X": 75,
"FY": 2012,
"ServiceType": "Employment Services",
"CostInMillions":      41.298085,
"Cost1kSvd":     5205203.55 
},
{
 "X": 76,
"FY": 2012,
"ServiceType": "Equipment",
"CostInMillions":       0.829144,
"Cost1kSvd":      104505.17 
},
{
 "X": 77,
"FY": 2012,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     175.699641,
"Cost1kSvd":    22145152.63 
},
{
 "X": 78,
"FY": 2012,
"ServiceType": "Hospital-based Services",
"CostInMillions":      29.670014,
"Cost1kSvd":     3739603.48 
},
{
 "X": 79,
"FY": 2012,
"ServiceType": "Medication",
"CostInMillions":      16.318993,
"Cost1kSvd":     2056843.08 
},
{
 "X": 80,
"FY": 2012,
"ServiceType": "Other",
"CostInMillions":       0.279391,
"Cost1kSvd":       42851.38 
},
{
 "X": 81,
"FY": 2012,
"ServiceType": "Outpatient Treatment",
"CostInMillions":       18.95636,
"Cost1kSvd":     2389256.37 
},
{
 "X": 82,
"FY": 2012,
"ServiceType": "Physical Health Services",
"CostInMillions":      11.806161,
"Cost1kSvd":     1488046.51 
},
{
 "X": 83,
"FY": 2012,
"ServiceType": "Screening & Assessment",
"CostInMillions":      13.291204,
"Cost1kSvd":     1675221.07 
},
{
 "X": 84,
"FY": 2012,
"ServiceType": "Transportation",
"CostInMillions":        2.71721,
"Cost1kSvd":      342476.68 
},
{
 "X": 85,
"FY": 2013,
"ServiceType": "Care Coordination",
"CostInMillions":      62.491678,
"Cost1kSvd":        7584862 
},
{
 "X": 86,
"FY": 2013,
"ServiceType": "Crisis and Respite",
"CostInMillions":       6.349919,
"Cost1kSvd":      770714.77 
},
{
 "X": 87,
"FY": 2013,
"ServiceType": "Employment Services",
"CostInMillions":      38.932099,
"Cost1kSvd":     4725342.76 
},
{
 "X": 88,
"FY": 2013,
"ServiceType": "Equipment",
"CostInMillions":       1.144716,
"Cost1kSvd":      138938.71 
},
{
 "X": 89,
"FY": 2013,
"ServiceType": "Home & Community Based Services",
"CostInMillions":     182.226429,
"Cost1kSvd":    22117542.06 
},
{
 "X": 90,
"FY": 2013,
"ServiceType": "Hospital-based Services",
"CostInMillions":      30.654286,
"Cost1kSvd":     3720631.87 
},
{
 "X": 91,
"FY": 2013,
"ServiceType": "Medication",
"CostInMillions":       7.625619,
"Cost1kSvd":      925551.52 
},
{
 "X": 92,
"FY": 2013,
"ServiceType": "Other",
"CostInMillions":       0.882651,
"Cost1kSvd":      107130.84 
},
{
 "X": 93,
"FY": 2013,
"ServiceType": "Outpatient Treatment",
"CostInMillions":      22.203813,
"Cost1kSvd":     2694964.56 
},
{
 "X": 94,
"FY": 2013,
"ServiceType": "Physical Health Services",
"CostInMillions":      23.318153,
"Cost1kSvd":     2830216.41 
},
{
 "X": 95,
"FY": 2013,
"ServiceType": "Screening & Assessment",
"CostInMillions":       14.15695,
"Cost1kSvd":     1718284.99 
},
{
 "X": 96,
"FY": 2013,
"ServiceType": "Transportation",
"CostInMillions":       2.707066,
"Cost1kSvd":       328567.3 
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
          
         
        
          
        chart.xAxis
  .axisLabel("Year")
  .width(    62)

        
        
        chart.yAxis
  .axisLabel("Total cost, in millions")
  .width(    62)
      
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

*Data from* [Open404](https://github.com/j-hagedorn/open404)

--- .class #id 

## Context: Variation...


<div id = 'chart37302f1843e7' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart37302f1843e7()
    });
    function drawchart37302f1843e7(){  
      var opts = {
 "dom": "chart37302f1843e7",
"width":    800,
"height":    400,
"x": "CMHSP",
"y": "CostPerUnit",
"group": "FirstofService.Description",
"type": "multiBarChart",
"id": "chart37302f1843e7" 
},
        data = [
 {
 "X": 1,
"CMHSP": "Bay-Arenac",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         552.21,
"UnitPerPerson":            6.1,
"CostPerPerson":        3347.99,
"SumOfCases": 429,
"SumOfCost": 1436289,
"Perc_Svd":            7.6 
},
{
 "X": 2,
"CMHSP": "Bay-Arenac",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         660.04,
"UnitPerPerson":            8.9,
"CostPerPerson":        5903.67,
"SumOfCases": 18,
"SumOfCost": 106266,
"Perc_Svd":            0.3 
},
{
 "X": 3,
"CMHSP": "Bay-Arenac",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         340.35,
"UnitPerPerson":             99,
"CostPerPerson":       33695.12,
"SumOfCases": 8,
"SumOfCost": 269561,
"Perc_Svd":            0.1 
},
{
 "X": 4,
"CMHSP": "Clinton Eaton Ingham",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         437.98,
"UnitPerPerson":           12.5,
"CostPerPerson":        5457.02,
"SumOfCases": 731,
"SumOfCost": 3989084,
"Perc_Svd":            9.4 
},
{
 "X": 5,
"CMHSP": "Clinton Eaton Ingham",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         624.92,
"UnitPerPerson":           85.4,
"CostPerPerson":       53360.91,
"SumOfCases": 67,
"SumOfCost": 3575181,
"Perc_Svd":            0.9 
},
{
 "X": 6,
"CMHSP": "CMH for Central Michigan",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         647.49,
"UnitPerPerson":            6.8,
"CostPerPerson":        4376.79,
"SumOfCases": 466,
"SumOfCost": 2039586,
"Perc_Svd":            5.7 
},
{
 "X": 7,
"CMHSP": "CMH for Central Michigan",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         748.67,
"UnitPerPerson":            8.1,
"CostPerPerson":        6069.02,
"SumOfCases": 47,
"SumOfCost": 285244,
"Perc_Svd":            0.6 
},
{
 "X": 8,
"CMHSP": "CMH for Central Michigan",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         502.07,
"UnitPerPerson":          181.4,
"CostPerPerson":       91097.44,
"SumOfCases": 18,
"SumOfCost": 1639754,
"Perc_Svd":            0.2 
},
{
 "X": 9,
"CMHSP": "Gratiot",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         647.99,
"UnitPerPerson":            6.8,
"CostPerPerson":        4434.41,
"SumOfCases": 83,
"SumOfCost": 368056,
"Perc_Svd":            5.2 
},
{
 "X": 10,
"CMHSP": "Gratiot",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         603.36,
"UnitPerPerson":            3.6,
"CostPerPerson":        2159.39,
"SumOfCases": 38,
"SumOfCost": 82057,
"Perc_Svd":            2.4 
},
{
 "X": 11,
"CMHSP": "Gratiot",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         518.42,
"UnitPerPerson":          115.7,
"CostPerPerson":          59964,
"SumOfCases": 3,
"SumOfCost": 179892,
"Perc_Svd":            0.2 
},
{
 "X": 12,
"CMHSP": "Huron",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         591.75,
"UnitPerPerson":            8.9,
"CostPerPerson":        5271.99,
"SumOfCases": 77,
"SumOfCost": 405943,
"Perc_Svd":            6.8 
},
{
 "X": 13,
"CMHSP": "Huron",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         628.55,
"UnitPerPerson":            6.8,
"CostPerPerson":        4285.55,
"SumOfCases": 11,
"SumOfCost": 47141,
"Perc_Svd":              1 
},
{
 "X": 14,
"CMHSP": "Ionia",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         794.38,
"UnitPerPerson":           10.7,
"CostPerPerson":        8514.39,
"SumOfCases": 71,
"SumOfCost": 604522,
"Perc_Svd":            3.7 
},
{
 "X": 15,
"CMHSP": "Ionia",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         193.92,
"UnitPerPerson":           11.6,
"CostPerPerson":        2258.59,
"SumOfCases": 17,
"SumOfCost": 38396,
"Perc_Svd":            0.9 
},
{
 "X": 16,
"CMHSP": "Ionia",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         356.18,
"UnitPerPerson":           60.2,
"CostPerPerson":       21459.75,
"SumOfCases": 4,
"SumOfCost": 85839,
"Perc_Svd":            0.2 
},
{
 "X": 17,
"CMHSP": "Lifeways",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         526.26,
"UnitPerPerson":            8.2,
"CostPerPerson":        4300.48,
"SumOfCases": 728,
"SumOfCost": 3130747,
"Perc_Svd":           10.9 
},
{
 "X": 18,
"CMHSP": "Lifeways",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         610.13,
"UnitPerPerson":           11.7,
"CostPerPerson":        7150.78,
"SumOfCases": 150,
"SumOfCost": 1072617,
"Perc_Svd":            2.2 
},
{
 "X": 19,
"CMHSP": "Lifeways",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         560.35,
"UnitPerPerson":          167.2,
"CostPerPerson":       93696.68,
"SumOfCases": 19,
"SumOfCost": 1780237,
"Perc_Svd":            0.3 
},
{
 "X": 20,
"CMHSP": "Montcalm",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         756.22,
"UnitPerPerson":            7.9,
"CostPerPerson":        6000.98,
"SumOfCases": 124,
"SumOfCost": 744121,
"Perc_Svd":           11.4 
},
{
 "X": 21,
"CMHSP": "Montcalm",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         725.83,
"UnitPerPerson":            9.3,
"CostPerPerson":        6765.79,
"SumOfCases": 28,
"SumOfCost": 189442,
"Perc_Svd":            2.6 
},
{
 "X": 22,
"CMHSP": "Montcalm",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         472.27,
"UnitPerPerson":             90,
"CostPerPerson":          42504,
"SumOfCases": 5,
"SumOfCost": 212520,
"Perc_Svd":            0.5 
},
{
 "X": 23,
"CMHSP": "Newaygo",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         673.53,
"UnitPerPerson":            9.9,
"CostPerPerson":        6679.18,
"SumOfCases": 84,
"SumOfCost": 561051,
"Perc_Svd":            4.5 
},
{
 "X": 24,
"CMHSP": "Newaygo",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         616.91,
"UnitPerPerson":           12.8,
"CostPerPerson":        7904.12,
"SumOfCases": 16,
"SumOfCost": 126466,
"Perc_Svd":            0.9 
},
{
 "X": 25,
"CMHSP": "Newaygo",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":          611.9,
"UnitPerPerson":             52,
"CostPerPerson":       31818.67,
"SumOfCases": 3,
"SumOfCost": 95456,
"Perc_Svd":            0.2 
},
{
 "X": 26,
"CMHSP": "Saginaw",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":          593.1,
"UnitPerPerson":           10.3,
"CostPerPerson":        6092.41,
"SumOfCases": 474,
"SumOfCost": 2887804,
"Perc_Svd":           10.6 
},
{
 "X": 27,
"CMHSP": "Saginaw",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         549.46,
"UnitPerPerson":           12.3,
"CostPerPerson":        6765.25,
"SumOfCases": 16,
"SumOfCost": 108244,
"Perc_Svd":            0.4 
},
{
 "X": 28,
"CMHSP": "Saginaw",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         462.28,
"UnitPerPerson":            168,
"CostPerPerson":       77663.44,
"SumOfCases": 27,
"SumOfCost": 2096913,
"Perc_Svd":            0.6 
},
{
 "X": 29,
"CMHSP": "Shiawassee",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         561.79,
"UnitPerPerson":            7.8,
"CostPerPerson":        4370.58,
"SumOfCases": 168,
"SumOfCost": 734258,
"Perc_Svd":           10.2 
},
{
 "X": 30,
"CMHSP": "Shiawassee",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         795.44,
"UnitPerPerson":            9.5,
"CostPerPerson":        7520.55,
"SumOfCases": 11,
"SumOfCost": 82726,
"Perc_Svd":            0.7 
},
{
 "X": 31,
"CMHSP": "Shiawassee",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         275.49,
"UnitPerPerson":             75,
"CostPerPerson":          20662,
"SumOfCases": 4,
"SumOfCost": 82648,
"Perc_Svd":            0.2 
},
{
 "X": 32,
"CMHSP": "Tuscola",
"FirstofService.Description": "Local Psychiatric Hospital - Acute Community PT73",
"CostPerUnit":         583.06,
"UnitPerPerson":            7.7,
"CostPerPerson":        4487.94,
"SumOfCases": 109,
"SumOfCost": 489185,
"Perc_Svd":            8.8 
},
{
 "X": 33,
"CMHSP": "Tuscola",
"FirstofService.Description": "Local Psychiatric Hospital/IMD PT68",
"CostPerUnit":         562.46,
"UnitPerPerson":            6.8,
"CostPerPerson":        3796.62,
"SumOfCases": 8,
"SumOfCost": 30373,
"Perc_Svd":            0.6 
},
{
 "X": 34,
"CMHSP": "Tuscola",
"FirstofService.Description": "State Psychiatric Hospital - Inpatient PT22",
"CostPerUnit":         442.11,
"UnitPerPerson":          108.2,
"CostPerPerson":       47858.75,
"SumOfCases": 4,
"SumOfCost": 191435,
"Perc_Svd":            0.3 
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
  .color([ "#bdc9e1", "#67a9cf", "#02818a" ])
          
        chart.xAxis
  .axisLabel("CMHSP")
  .width(    62)

        
        
        chart.yAxis
  .axisLabel("Cost per day, 2013")
  .width(    62)
      
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

*Data from* [Open404](https://github.com/j-hagedorn/open404)

--- .class #id 

## Context: Integration
(- Redundancy) (- Stigma) (+ Science) -> Integration

>- Redundant systems, admin functions

>- Less stigma

>- Innovations in science (genomics,upstream factors,&c.)

--- .class #id 

## Remaking the Public Behavioral Health System

>- Open Knowledge

>- Public System Entrepeneurs

>- Designed to address "wicked" problems

--- .class #id 

## "Wicked" Problems: Characteristics
(*term borrowed from design thinking)

1. No universal definition
2. Improve, not solve
3. Many causes
4. Interconnected
5. No single measure of success

--- .class #id 

## ONLY THE DIFFICULT INSPIRES THE NOBLE-HEARTED 

Can any one person fathom this situation?

>- No.   Enter data.

>- Not a "single source of truth," but a shared situation.

*** =pnotes
Title quote by S. Kierkegaard
System 1 v System 2 
We overestimate the effects of our actions
In unpredictable situations, our inconsistency wrecks validity

--- .class #id 

## Making it useful

What information would you need to make you change the way you live?

>- What's the issue? (Measures, Analysis)
>- What to do? (Levers)
>- What's success? (Target)

--- .class #id 

## FACT IS THE SWEETEST DREAM THAT LABOR KNOWS

* Stigma: When do labels become characteristics?

* Self-tracking as empowerment
([Quantified Self](http://quantifiedself.com/))

* Self-monitoring helps (obesity, bipolar)

* Use of data in a clinical context
([Boswell, et al, 2013](http://www.scottdmiller.com/wp-content/uploads/2014/06/Implementing-routine-outcome-monitoring-in-clinical-practice-Benefits-challenges-and-solutions-Psychotherapy-Research_Boswell-Kraus-Mi.pdf))

* Frequent, consistent 
([Peterson, et al. 2014](http://onlinelibrary.wiley.com/doi/10.1002/oby.20807/full))

--- .class #id 

## To Do List:

* Key Questions
* Identify Levers
* Build Measures
* Get Data
* Analyze Data
* Communication
* Build Data Literacy
* Integrate into Process
* Use Data

--- .class #id 

## Ask Real Questions

Based on contextual themes:
* Quality
* Cost / Resource Use
* Integration / Coordination

--- .class #id

## Data Lab

--- .class #id

## Homework
1. Identify data points currently measured which are relevant for you in your role.
2. Identify 2 ways that you could usefully integrate data into your clinical practice (e.g. supervision, pre-PCP meetings, etc.)

--- .class #id

<style> 
.title-slide {
  background-color: #ffffff; /* #EDE0CF; ; #CA9F9D*/
  /* background-image:url(http://goo.gl/EpXln); */
} 
</style>
