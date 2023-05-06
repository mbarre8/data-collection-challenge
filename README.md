# data-collection-challenge

The following challenge I web scrapped and analyzed two different webpages. 

In part one of the challenge I used chrome devtools, splinter, beautifulsoup to parse through the data. I located the text elements and provide of list of article titles and their previews in a jupyter notebook. 

In part two of the challenge I used the same tools as part one to parse through the a webpage looking at mars temperature data. In addition, I used matplotlib and pandas to further aggregate the data on the webpage and plot graphs. I exported the graphs(as PNG images) for average low temperature by month, average low temperature by coldest to hottest months, the average pressure by month, and number of terrestrial days in a martin year using minimum temperature to a folder called data. In addition I exported the Dataframe(as a CSV file) to the same folder above. I also answered the following questions:

1)How many months are there on Mars?
Month Total
1     174
2     178
3     192
4     194
5     149
6     147
7     142
8     141
9     134
10    112
11    138
12    166

2) How many Martian days' worth of data are there?
There is 1867 Martian days' worth of data.

3)What is the average low temperature by month?

Month   Average Low Temperature
1       -77.160920
2       -79.932584
3       -83.307292
4       -82.747423
5       -79.308725
6       -75.299320
7       -72.281690
8       -68.382979
9       -69.171642
10      -71.982143
11      -71.985507
12      -74.451807

4) Average pressure by Martian month:

Month Average Pressure 
1     862.488506
2     889.455056
3     877.322917
4     806.329897
5     748.557047
6     745.054422
7     795.105634
8     873.829787
9     913.305970
10    887.312500
11    857.014493
12    842.156627


