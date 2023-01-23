# Twitter Scrapping

## Project Description

Scrapping data from Twitter using snscrape, manitaining the data using MongoDB and Create a GUI using streamlit. 

### Skills Used:


<a href="https://datasciencedojo.com/blog/scrape-twitter-data-using-sncrape/">
<img alt="snscrape" src="https://i.ytimg.com/vi/QLIYJoRvd-M/maxresdefault.jpg" width="165"/>
</a>
<a href="https://pandas.pydata.org/docs/reference/index.html">
<img alt="Pandas" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/2560px-Pandas_logo.svg.png" width="165"/>
</a>
<a href="https://pymongo.readthedocs.io/en/stable/tutorial.html">
<img alt="MongoDB" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/MongoDB_Logo.svg/2560px-MongoDB_Logo.svg.png" width="165"/>
</a>
<a href="https://www.datacamp.com/tutorial/streamlit">
<img alt="Streamlit" src="https://streamlit.io/images/brand/streamlit-logo-primary-colormark-darktext.png" width="165"/>
</a>


## Problem Statement
 
Today, data is scattered everywhere in the world. Especially in social media, there may be a big quantity of data on Facebook, Instagram, Youtube, Twitter, etc. 
This consists of pictures and films on Youtube and Instagram as compared to Facebook and Twitter. To get the real facts on Twitter, you want to scrape the data from Twitter. You Need to Scrape the data like (date, id, url, tweet content, user,reply count, retweet count,language, source, like count etc) from twitter.

## Work Flow

- _**Scrapping the Data using snscrape**_
   
- _**Creating DataFrame**_
  - Dataframe with date, id, url, tweet content, user,reply count, retweet count,language, source, like count.

- _**Maintaining Data in MongoDB**_
  - Storing each collection of data into a document into Mongodb along with the hashtag or key word we use to  Scrape from twitter. eg:({“LIC corporation+current Timestamp”: [{1000  Scraped data from past 100 days }]})
  
- _**GUI using Streamlit**_
  - Creating a GUI using streamlit that contains the feature to enter the keyword or Hashtag to be searched, the date range and limit the tweet count need to be scraped. After scraping, the data is displayed in the page and user can do the following actions such as uploading the data into Database and downloading the data into csv and json format using buttons.

## License

The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported license](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](LICENSE.md).
