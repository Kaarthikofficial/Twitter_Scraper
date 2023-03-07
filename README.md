# Twitter_Scraper
This project is done with the vision to scrape data from twitter by using keywords or hashtags

## About:

	An app with multiple features to scrape, download and upload data to database created with the help of Python, Streamlit, MongoDB.
*	One can search for any keyword or hashtag and scrape the required number of records.
*	If the data needs to be in local, two download formats are available inside the app
*	Finally, if the records needs to get uploaded into database there is an option available to do the same.

## Workflow
1. The app is built with the options to get input from users like keyword/hashtag, data from, date till, count of tweets to retrieve. 
2. By using snscrape library, import the twitter module and with the help of functions TwitterSearchScraper and TwitterHashtagScrapper 
   scraped the required contents from twitter.
3. Once scraped it will be displayed in the screen along with the options to download and upload.
4. User can download in two available formats CSV or JSON.

## Learning outcomes
- Streamlit
- Snscrape
- Mongodb
