# Coachella-Weekend-2-Tweets

Project Scope: 
- We hope to identify the reactions of the people to the lineup of the artists at the music festival, i.e., the artists that were liked and who were not liked much so that the music festival can improve its lineup for the next year. We also hope that this dataset can be used for identifying the different elements of a music festival that people get excited enough to tweet about, either because they were successful or because they needed improvement. Also, we hope that this dataset can identify reasons why people attended the music festival, which could be used for future marketing efforts.

Data Source:
- As of now, we are only obtaining data from Twitter, and not across a range of other social media platforms such as Facebook and Instagram, which could also provide good insights. In future years, gathering data from those sources may be beneficial as well.

Challenges:
- Not able to use a Streaming API – we were not able use it as Coachella was held in April.
- The Standard API search request only goes back 7-days, so running a search for (…, q = ‘Coachella’, …) would not work without some starting information like tweet_id or screen_name
  - Solution: Found a kaggle dataset related to our topic that allowed us to gather the necessary information to run some standard API searches with Twython. Link Here(https://www.kaggle.com/pdp2600/coachella-2019-tweets)

Final Datasets
- Artist Lineup Dictionary: a json dictionary where the keys are all the artists that performed at Coachella and the values are the information related to their set times (start time, end time, stage, etc.)
  - Artist set information scraped from Pitchfork (https://pitchfork.com/news/coachella-2019-lineup-and-schedule-all-the-set-times-you-need-to-know/)
- Tweet ID Dictionaries: the collection tweet IDs from the Weekend 2 of Coachella, grouped by hour, with each JSON file separated by day.

Code Implementation
- Use the 'Retrieving Tweet Dictionary for Coachella Artists' jupyter file as example of how to access the full tweet objects for all tweets sent during a specified artist's set time at Coachella.






