# soup-challenge
Project Overview
This project involves the scraping and analysis of Martian weather data collected from a publicly available website. The goal is to gather information about Mars' temperature, atmospheric pressure, and seasonal patterns using web scraping tools and then analyze the data using Python libraries like Pandas and Matplotlib. The insights derived from the analysis help us understand how conditions on Mars change over time.

Objectives
The project consists of two key deliverables:

Scraping Mars News Articles: Extracting titles and preview text from a Mars news site using BeautifulSoup and Splinter.
Scraping and Analyzing Mars Weather Data: Scraping weather data in the form of a table and performing detailed analysis on Martian temperatures and atmospheric pressure.
Deliverables

1. Scraping Mars News Articles
Tools Used: Splinter (for automated browsing) and BeautifulSoup (for HTML parsing).
Task: Visited a Mars news site and extracted the titles and preview text for the latest news articles. The data was stored in a Python dictionary and printed for verification.

2. Scraping and Analyzing Mars Weather Data
Tools Used: Splinter, BeautifulSoup, Pandas, and Matplotlib.
Task: Scraped weather data from a Mars weather site, which contains details about minimum temperatures, atmospheric pressure, and more.

Data Organization: The scraped data was stored in a Pandas DataFrame with the following columns:
id: Data transmission ID.
terrestrial_date: Earth date of the observation.
sol: Martian day since landing.
ls: Solar longitude.
month: Martian month.
min_temp: Minimum temperature on that Martian day (in °C).
pressure: Atmospheric pressure on that Martian day (in Pa).

Analysis Performed
Data Cleaning: Converted data types appropriately to enable analysis (e.g., dates were converted to datetime, numeric values were cast correctly).

Data Insights:

Number of Months on Mars: Identified that there are 12 months on Mars based on the available data.

Martian Days of Data: Calculated that there are 1867 sols (Martian days) worth of data.

Average Minimum Temperature by Month: Calculated the average minimum temperature for each Martian month and identified:

Coldest Month: Month 3, with an average minimum temperature of approximately -83.3°C.

Hottest Month: Month 8, with an average minimum temperature of approximately -68.4°C.

Average Atmospheric Pressure by Month: Calculated the average atmospheric pressure for each Martian month and identified:

Lowest Pressure Month: Month 6, with an average pressure of 745 Pa.

Highest Pressure Month: Month 9, with an average pressure of 913 Pa.

Martian Year Length: Using temperature data over time, visually estimated the length of a Martian year to be approximately 687 Earth days, which aligns with scientific knowledge.

Visualizations
The project includes the following visualizations:

Average Minimum Temperature by Month on Mars: A bar chart showing the temperature variation throughout the Martian year.

Average Atmospheric Pressure by Month on Mars: A bar chart visualizing the changes in atmospheric pressure across different months.

Daily Minimum Temperature on Mars Over Time: A line graph plotting the daily minimum temperatures over terrestrial (Earth) dates, used to estimate the length of a Martian year.
Data Export
The final cleaned and analyzed dataset was exported to a CSV file (mars_weather_data.csv) for easy sharing and further analysis.

How to Run the Code
Clone the repository to your local machine.
Ensure you have the necessary Python packages installed (Splinter, BeautifulSoup, Pandas, Matplotlib).
Run the Jupyter Notebook files for each part of the project to execute the scraping, data cleaning, analysis, and visualization steps.
Check the generated visualizations and CSV file for insights into Mars' weather.
