# Mission-to-Mars

## Overview

The purpose is to explore mars data using web-scraping and data analysis, through this project I wiil scrape, organize, analyze, and visualize the data.

## Resources
- Python
- Web Scrapping
- Beautiful Soups object
- Chrome Driver
- Sources : https://redplanetscience.com & https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html

## Results

First, I navigated to Mars NASA news site: https://redplanetscience.com to build a JSON file with the title and preview of all articles in this webpage. This was posible thanks to a beutiful soup object that enabled web scrapping as you may consult in part_1_mars_news.ipynb file.

<img width="618" alt="Screen Shot 2023-02-25 at 12 28 33" src="https://user-images.githubusercontent.com/114015620/221373655-e44546b4-acae-446b-93a7-c885f0dfcc8d.png">

After this, Mars weather was explored. Data was imported through pandas read_html. Once data was ready in the notebook, data preparation followed to have the dataset ready for analysis

<img width="561" alt="Screen Shot 2023-02-25 at 12 32 00" src="https://user-images.githubusercontent.com/114015620/221373791-c3184045-0cb3-4332-b8df-49e25bae574a.png">

### Analysis

How many months exist on Mars?

<img width="333" alt="Screen Shot 2023-02-25 at 12 32 40" src="https://user-images.githubusercontent.com/114015620/221373819-fa21a45a-e6b8-45d4-8b99-c302181a2188.png">

How many Martian (and not Earth) days worth of data exist in the scraped dataset?

<img width="439" alt="Screen Shot 2023-02-25 at 12 33 28" src="https://user-images.githubusercontent.com/114015620/221373852-5946497e-d474-436d-be9a-f3742543f9e7.png">

What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Average the minimum daily temperature for all of the months.

<img width="509" alt="Screen Shot 2023-02-25 at 12 35 39" src="https://user-images.githubusercontent.com/114015620/221373943-98130761-b082-4874-8e81-207643c50481.png">
Results in a bar plot

<img width="612" alt="Screen Shot 2023-02-25 at 12 36 14" src="https://user-images.githubusercontent.com/114015620/221373964-1de82632-0cf6-415b-a59c-0a308e5faad7.png">

Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average the daily atmospheric pressure of all the months.

<img width="560" alt="Screen Shot 2023-02-25 at 12 40 41" src="https://user-images.githubusercontent.com/114015620/221374133-81cb6b18-0ec6-4cc3-8a16-bbb429381cdd.png">

Plot the results as a bar chart.

<img width="586" alt="Screen Shot 2023-02-25 at 12 41 07" src="https://user-images.githubusercontent.com/114015620/221374153-867ade43-4166-49df-984f-763977bb4cbf.png">

About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

<img width="588" alt="Screen Shot 2023-02-25 at 12 41 34" src="https://user-images.githubusercontent.com/114015620/221374181-ccf15831-880b-449c-8baf-36625c4efb26.png">



