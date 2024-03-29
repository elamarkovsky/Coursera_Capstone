# Coursera_Capstone
Analysis of Israeli restaurants in New York City

Introduction

The 2000 United States Census estimated that as many as 106,839 Israelis live in the United States, while other unsourced estimates say the number is much higher, around 500,000 . New York City is the city where most Israeli-Americans reside . Immigrants tend to bring their cuisine with them and Israelis are no exception, evidenced by new Israeli restaurants constantly popping up in New York City .
In this project I plan to analyze Israeli restaurants in New York City and obtain the number of restaurants by borough, their ratings and the number of ratings they receive. This analysis would be valuable to people who consider opening a restaurant serving Israeli cuisine. This analysis will help determine whether there is a sufficient demand for such restaurants and in which borough it would be best to open one. This analysis would also be of interest to Israeli-Americans and anyone who enjoys Israeli cuisine.

Data

Data on names and locations was collected from Foursquare by making a basic request for restaurants labeled as “Israeli”. The request was made using latitude and longitude of NYC with a radius of 15000. Foursquare location data for a restaurant does not include the borough, therefore a separate dataset (https://www.health.ny.gov/statistics/cancer/registry/appendix/neighborhoods.htm),  was used to assign each restaurant to the borough according to its zip code. A separate premium request was made for each restaurant to get their rating and number of ratings. These ratings were saved to avoid making multiple premium requests.

References

  https://en.wikipedia.org/wiki/Israeli_Americans
 https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=DEC_00_110S_QTP13&prodType=table
  http://www.grubstreet.com/2017/06/rise-of-israeli-cuisine-in-new-york.html
