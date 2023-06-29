# Mars News and Weather Analysis
This project is focused on web-scraping and data analysis of information related to Mars. The project consists of two parts: Part 1 is a Jupyter notebook containing code that scrapes the Mars news titles and preview text. Part 2 is a Jupyter notebook containing code that scrapes the Mars weather data and that cleans, visualizes, and analyzes that data.

# Technical Skills
- Webscraping 
- Splinter
- Beautiful Soup
- Data analysis using Pandas
- Plotting charts using Matplotlib

# Weather Analysis
## #1. How many months exist on Mars?
<img src="https://user-images.githubusercontent.com/109693942/217193063-6754345d-a6c4-4451-80d4-54b2cffc69f9.JPG" width="40%" height="40%">


### 12 months exist on Mars
<hr>

## #2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
<img src="https://user-images.githubusercontent.com/109693942/217194635-00a99344-484a-4811-8b49-c157408b9393.JPG" width="40%" height="40%">


### 1867 days worth of data
<hr>

## #3. What are the coldest and the warmest months on Mars (at the location of Curiosity)?
<img src="https://user-images.githubusercontent.com/109693942/217194826-32cafe8a-5c50-4f8d-9220-7e222dcd1d6e.JPG" width="40%" height="40%">

<img src="https://user-images.githubusercontent.com/109693942/217194886-205b4666-b1b1-42b9-ba5e-ad5bf137e75f.JPG" width="40%" height="40%">

### On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the "warmest". But it is always very cold there in human terms!
<hr>

## #4. Which months have the lowest and the highest atmospheric pressure on Mars?
<img src="https://user-images.githubusercontent.com/109693942/217195178-eb9e2197-d6f0-41e0-b94f-f93df9f62d7d.JPG" width="40%" height="40%">

<img src="https://user-images.githubusercontent.com/109693942/217195202-98a93995-8c1a-4131-86ee-b755b3ea3f58.JPG" width="40%" height="40%">

### Month 6 has the lowest atmospheric pressure, while month 9 has the highest
<hr>

## #5. About how many terrestrial (Earth) days exist in a Martian year?
<img src="https://user-images.githubusercontent.com/109693942/217193771-993e17e6-38fa-43e3-b19e-642ceca73d38.JPG" width="40%" height="40%">

### There are 687 Earth days in a Martian year. As visualized by the chart, the distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
<hr>

# Project Parameters
- Deliverable 1: Scrape Titles and Preview Text from Mars News (40 points)
    - Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup)
    - The titles and preview text of the news articles were scraped and extracted
    - The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries

- Deliverable 2: Scrape and Analyze Mars Weather Data
    - The HTML table was extracted into a Pandas DataFrame. Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types
    - The data was analyzed to answer all five listed questions, with data visualizations provided when specified
    - The DataFrame was exported into a CSV file 
