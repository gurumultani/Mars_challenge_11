# Mars_challenge_11
### Part 1

Mars News Data Scraping

This project involves scraping Mars news data from a website, storing the data in Python data structures, and printing the results.
Steps

1. Visit the Website: We use automated browsing to visit the Mars News Site. We inspect the page to identify which elements to scrape.

2. Scrape the Website: We create a Beautiful Soup object and use it to extract text elements from the website. We extract the title and preview text of each news article.

3. Store the Results: We store the titles and preview text of the news articles that we scraped. Each title-and-preview pair is stored in a Python dictionary with two keys: title and preview. All the dictionaries are stored in a Python list. We print the list to confirm success.
Libraries Used

- splinter: For automated browsing.
- BeautifulSoup: For parsing HTML and scraping web data.

#### Part 2

Mars Weather Data Analysis

This project involves scraping Mars weather data from a website, storing the data in a Pandas DataFrame, and performing some basic data analysis.
Steps

1. Visit the Website: We use automated browsing to visit the Mars Temperature Data Site. We inspect the page to identify which elements to scrape.

2. Scrape the Table: We create a Beautiful Soup object and use it to scrape the data in the HTML table. We extract all rows of data and store them in a list.

3. Store the Data: We assemble the scraped data into a Pandas DataFrame. The columns have the same headings as the table on the website.

4. Prepare Data for Analysis: We examine the data types that are currently associated with each column. If necessary, we cast (or convert) the data to the appropriate datetime, int, or float data types.

5. Analyse the Data: We analyse the dataset by using Pandas functions to answer the following questions:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)?
- Which months have the lowest and the highest atmospheric pressure on Mars?
- About how many terrestrial (Earth) days exist in a Martian year?

6. Save the Data: We export the DataFrame to a CSV file for future use.
Libraries Used

- splinter: For automated browsing.
- BeautifulSoup: For parsing HTML and scraping web data.
- pandas: For data manipulation and analysis.
- matplotlib.pyplot: For creating static, animated, and interactive visualizations in Python.


