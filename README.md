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

  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/c5de85af-32c7-40d4-a668-d6f891817f66)

  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/de9abaed-ccb9-4c1a-a1ac-e36f3cb16af5)

  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/1b0918a8-fab0-4020-bab9-0b36a2b5afb8)
 
  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/9a77cf40-898b-4914-b94c-5258a7b859ea)

  ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/f4ffbb64-542c-49b2-bea6-1770cde1e0a8)

- The data was analyzed to answer the following questions:

  - How many months exist on Mars?
 
    ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/215b71d2-c269-4361-93a0-efd1580d92ee)
  
  - How many Martian days' worth of data are there?
 
    ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/1a354a2c-3671-4fcf-8cf0-63d4836d3e64)

  - The data was analyzed to answer the following questions, and a data visualization was created to support each answer:
  
    - Which month, on average, has the lowest temperature? The highest?
   
      ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/d9807b5b-17d7-478f-aede-87751bffd11d)
 
      Answer: On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest.

    - Which month, on average, has the lowest atmospheric pressure? The highest?
   
      ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/60f1d236-80ad-4f72-9463-148f4957a0b7)
 
      Answer: Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
 
    - How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
   
      ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/cb83fa0c-cfca-4ae0-aab3-1df531b45b20)

      ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/c1228314-41d6-43a7-9f48-f2f0df239aff)

    - The DataFrame was exported into a CSV file.

      ![image](https://github.com/CourtneyCole123/mars_weather_data/assets/162069113/8a70d210-77ea-4bb8-96ea-801d4dba5e2a)
