# html-css-data-collection

This project was divided into two parts. 

Part 1 was aimed at creating a BeautifulSoup object to scrape the Mars headlines website for text relating to articles. The text was stored into a dictionary and then was read or extracted using a for loop. As such, the first page of headlines was stored into two keys: title and preview.

Part 2 was aimed at scraping another website relating to Mars facts, but the facts were located on a table. The goal of scraping the website was to scrape each row of data and then store that data into a Pandas DataFrame. Once stored, analysis was run on the DataFrame to find averages and create visualizations for the average temperatures and atmospheric pressures that exist on Mars for the different months. Finally, the DataFrame was exported to a csv file.

