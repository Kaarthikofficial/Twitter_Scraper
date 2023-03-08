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

## To run the same locally
- Install python in your system and create a path in environment 
  by using edit environment variables in control panel or settings.
- Now download the scraper file in my repository along with requirements file.
- Open the folder where you downloaded the file and run cmd in the path
- By using the command prompt, run pip install -r requirements.txt. Once after
  that, type streamlit run (downloaded file name).py and enter
- Now, you will get the app ready in your browser
- If you wish to upload in your local database. You can make use of upload button available

### Following is the link for my app
https://kaarthikofficial-twitter-scraper-scraper-joa2hn.streamlit.app/
***You can only download the data since uploading into database will redirect to the local db which is mongodb***
