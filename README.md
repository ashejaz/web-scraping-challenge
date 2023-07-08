## Overview

For this challenge, Chrome DevTools was used to inspect two websites containing data about Mars, and BeautifulSoup was used to extract the html data. A series of analyses were then performed using Pandas and the relevant visualisations were created using Matplotlib.

## Part 1: MarsNews

Article header and summary data was extracted from the following site: https://static.bc-edx.com/data/web/mars_news/index.html

A list of dictionaries was created to store this data which was then exported as a JSON file.

- The script can be found in the 'part_1_mars_news.ipynb' file in the MarsNews folder.
- The JSON file of extracted data can be found as 'news_list'.json in the MarsNews folder.

## Part 2: MarsWeather

A table of Mars weather data was extracted from the following site: https://static.bc-edx.com/data/web/mars_facts/temperature.html

The data was then added to a Pandas DataFrame, datatypes corrected and analysis performed.

The following results were found:
- There are 12 months on Mars.
- There are 1866 Martian days worth of data in this dataset.
- Month 3 has the lowest average minimum temperature, while month 8 has the highest:

![avg_temp](https://github.com/ashejaz/web-scraping-challenge/assets/127614970/0903ef97-4fb5-4b2a-9cfc-36a3b5cff5a8)

- Month 6 has the lowest average atmospheric pressure while month 9 has the highest:

![avg_pressure](https://github.com/ashejaz/web-scraping-challenge/assets/127614970/06db1772-fa6b-4b4e-9f4b-378f2831a3e3)

- There are approximately ~675 Earth days in a Martian year:

![temp_days](https://github.com/ashejaz/web-scraping-challenge/assets/127614970/b2e3f2f6-b65d-4ab7-b3d7-d649c8916186)

Once analysis had concluded, the DataFrame was exported as a CSV file.

- The script used can be found in the 'part_2_mars_weather.ipynb' file in the MarsWeather folder.
- The CSV file can be found as 'weather_data.csv' in the MarsWeather folder.
  
## References
The websites used in this challenge are operated by edX Boot Camps LLC with data retreived from https://mars.nasa.gov.
