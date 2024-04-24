# Module-11-Challenge
There are two parts for this challenge:
## 1: Scrape titles and preview text from Mars news articles.
In this part Mars news site is scraped with the help of  both automated browsing with Splinter and HTML parsing with Beautiful Soup.
In this part the following steps are performed:
 * Used automated browsing to visit the Mars news site,then inspected the page to identify which elements to scrape.
 * Created a Beautiful Soup object and extracted the text elements from the website.
 * Extracted all the text elements and stored as 'text'.
 * Created an empty list to store the scraped data dictionaries.
 * Extracted the title and preview text from the 'text' using for loop.
 * Stored each title and preview pair in a dictionary named 'text_dict'.
 * Added the dictionary to the list.
 * Printed the list.

## 2: Scrape and analyze Mars weather data, which exists in a table.
In this part Mars Temperature Data Site is scraped with the help of  both automated browsing with Splinter and HTML parsing with Beautiful Soup.The main objective of this part was to scrap the table element form the website.So that the following steps are performed.

 * Inspected the table and created  empty lists for each columns.
 * Looped through the scrapped data and retreived all cloumns and stored in the column lists.
 * Created a dataframe from the scrapped data.
 * Performed several data analysis as follows:

     * Changing the datatypes of the columns as intructed using 'datetime' and 'astype'.
     * Calculated how many months are there on Mars using 'value_counts'.
     * Calculated  how many Martian days are there using 'count'.
     * Calculated the average low temperature by month,performed 'groupby'.
     * Plot bar graph on the average temperature by month data.
     * Calculated the coldest and hottest months in Curiosity's location and plotted the data as a bar graph.
     * Calculated average pressure by Martian month using 'groupby'.
     * Ploted the pressure data as a bargraph.
     * Calculated how many terrestrial (earth) days are there in a Martian year and plotted the data as a line graph.

* Lastly saved the mars temperature dataframe as a csv file.


