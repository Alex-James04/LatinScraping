# Latin Texts Scraping

### Overview
- This project uses the Beautiful Soup Python library to scrape data from PHI Latin Texts (https://latin.packhum.org/browse). 
- The resulting main parquet file in this repo contains ~1.8 million entries each, with each row containing the total instances of a word per text per author, as well as a link to the text being referred to.
- The additional data-analysis parquet files manipulate the main parquet file to get key values relating to word frequency and diversity.
- The Power BI report linked below and included in the repo is a basic display of the scraped data, showing the number of times each word is used across the whole site, the total words by text, and the total words by author.

### Additional Information
- I attempted this project in order to gain familiarity with common web scraping tools, learn how to publish a basic Power BI report, and because it combines two of my vastly different areas of interest - computer/data science and Latin.
- If there are any concerns (i.e. the Power BI link doesn't work) or suggestions (i.e. ideas for more extensive analysis) for this project, please email me below.

### Future Applications
- This project could be the basis for a machine learning algorithm that identifies underlying patterns in authors' writing styles.
- An application of this could be identifying who wrote newly-discovered texts, although in order to realistically do this more inter-word data would be needed (word combination patterns, word order patterns, etc.).

### View Power BI report here:
Power BI Report: https://app.powerbi.com/view?r=eyJrIjoiNGYxZDQzNzQtOTU1NC00YzUwLWEwYTEtZTUxZTZiMDhjZDEzIiwidCI6IjdiMzQ4MGM3LTM3MDctNDg3My04Yjc3LWUyMTY3MzNhNjVhYyIsImMiOjF9

### Contact
Email: Ajames04321@gmail.com
