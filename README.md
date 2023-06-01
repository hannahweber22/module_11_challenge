# module_11_challenge

# In this challenge, for part 1, I scraped titles and preview text from Mars news articles. For part 2, I scraped and analyzed Mars weather data which existed in a table. For part 1, I used automated browsing to visit the Mars news site. I created a Beautiful Soup object and used it to extract text elements from the website. I extracted the titles and preview text of the news articles that I scraped, and I store the results in a Python dictionaries. A dictionary was created for each title and preview text. The dictionaries were stored in a Python list. I printed the list of dictionaries in my jupyter notebook. For part 2, I used automated browsing to visit the Mars Temperature Data Site. I created a Beautiful Soup object and use it to scrape the data in the HTML table. I assembled the scraped data into a Pandas DataFrame. The columns of data were id, terrestrial_date, sol, ls, month, min_temp, and pressure. The descritions of each column are listed below in Part 2 Column Description. I converted terrestrial_date to datetime; I converted sol, ls, and month to integers; I converted min_temp and pressure to floats. I analzyed the data to find 12 months exist on Mars, there are 1867 martian days worth of data, the coldest month on Mars is month 3, the warmest month on Mars is 8, month 6 has the lowest atmospheric pressure, month 9 has the highest atmospheric pressure, and there are about 675 terrestrial days in a Martian year. I exported the dataframe containing id, terrestrial_date, sol, ls, month, min_temp, and pressure to a csv called DataFrame.csv. 


# Part 2 Column Descriptions
    id: the identification number of a single transmission from the Curiosity rover
    terrestrial_date: the date on Earth
    sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
    ls: the solar longitude
    month: the Martian month
    min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
    pressure: The atmospheric pressure at Curiosity's location
