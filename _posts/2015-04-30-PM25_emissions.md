---
layout: post
categories: jekyll update
date: "2015-04-30 12:23:00"
title: PM 2.5 Emissions / Year / Sq Mile
...

These maps show PM 2.5 emissions by county across the United States from 1999 to
2008. You can read about the data here: [Clearinghouse for Inventories &
Emissions Factors][1] and download the data here: [Data.][2]

[1]: <http://www.epa.gov/ttn/chief/eiinformation.html>

[2]: <https://d396qusza40orc.cloudfront.net/exdata/data/NEI_data.zip>

I also pulled data showing the square miles of each county in the country from the Census Bureau America [Fact Finder website.][4] 

I did the work in R and figured out how to do the mapping from this post showing
how to map unemployment rate by county. [Choropleths in R][3]

See the repo [here][5]

[3]: <http://www.thisisthegreenroom.com/2009/choropleths-in-r/>

[4]: <http://factfinder.census.gov>

[5]: <https://github.com/IanMadd/MappingPM25> 

![1999 PM 2.5 Emissions](<{{site.url}}/assets/PM25Emissions1999.png>)

![2002 PM 2.5 Emissions](<{{site.url}}/assets/PM25Emissions2002.png>)

![2005 PM 2.5 Emissions](<{{site.url}}/assets/PM25Emissions2005.png>)

![2008 PM 2.5 Emissions](<{{site.url}}/assets/PM25Emissions2008.png>)
