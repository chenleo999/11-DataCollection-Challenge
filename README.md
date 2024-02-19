# 11-DataCollection-Challenge

completed by Li Chen, 2/19/2024

Part 1: Mars News

scrape web site https://static.bc-edx.com/data/web/mars_news/index.html
    collect title and preview of news artitles

steps:
Use automated browsing to visit the Mars news site, inspect the page
Create Beautiful Soup object to extract text elements
Extract the title and preview of news articles 
Store resultes as a list of Python dictionary
    each item has 2 keys: title and preview
Print out the list

Deliverable 1: part_1_mars_news.ipynb


Part 2 Mars Weather

scrape web site https://static.bc-edx.com/data/web/mars_facts/temperature.html
    collect table with Mar weather info

steps:
Use automated browsing to visit the Mars Temperature site, inspect the page
Create a Beautiful Soup object to extra data in HTML table
Assemble table row/column data into Pandas DataFrame
Convert data types properly

Analyze dataset and answer these questions:

How many months exist on Mars? 
month value count, 12

How many Martian (and not Earth) days worth of data exist in the scraped dataset? 
data length for not null sol(Martian days), 1867

What are the coldest and the warmest months on Mars (at the location of Curiosity)?
sort monthly average min_temp, coldest month: the 3rd month, warmest month: the 8th month

Which months have the lowest and the highest atmospheric pressure on Mars? 
sort monthly average pressure, lowest: the 6th month, highest: the 9th month

About how many terrestrial (Earth) days exist in a Martian year? 
according to terrestrial day temp plot, roughly peak to peak length is about 675 days.

Export DataFrame to CSV file

Deliverable 2: part_2_mars_weather.ipynb
Deliverable 3: mars.csv

