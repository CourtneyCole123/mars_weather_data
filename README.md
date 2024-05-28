## Part 1: Scrape Titles and Preview Text from Mars News 📰 ##

- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).

  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/0c5a753f-9e6e-4a58-b612-c6f3f1cf68e2)

- The titles and preview text of the news articles were scraped and extracted.

  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/5f76178e-32c2-4af2-b679-88013456f063)

- The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/c9f6a6c3-52bb-4380-9aa8-a27cb6b551e4)

  <pre> Special Note: https://stackoverflow.com/questions/3229419/how-to-pretty-print-nested-dictionaries was used as a reference to pretty print</pre>

## Part 2: Scrape and Analyze Mars Weather Data 🌧️ ##

- The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types.

- The data was analyzed to answer the following questions:

  - How many months exist on Mars?
  
  - How many Martian days' worth of data are there?
  
  - The data was analyzed to answer the following questions, and a data visualization was created to support each answer:
  
    - Which month, on average, has the lowest temperature? The highest?
    
    - Which month, on average, has the lowest atmospheric pressure? The highest?
    
    - How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
    
    - The DataFrame was exported into a CSV file.
