# Coachella-Weekend-2-Tweets

Each '4.XX.19 coachella tweets.json' file is a collection of tweet_id's grouped by hour, with the files separated by date.


Weekend Artist Lineup.json is the set of all artists who performed at coachella with their set information (start time, end time, stage)

Use the 'Retreiving Tweet Dictionary for Coachella Artists' jupyter file as example of how to access the full tweet objects for all tweets sent during a specified artist's set time at Coachella.


#new readme
Scope: 

We hope to identify the reactions of the people to the lineup of the artists at the music festival, i.e., the artists that were liked and who were not liked much so that the music festival can improve its lineup for the next year. We also hope that this dataset can be used for identifying the different elements of a music festival that people get excited enough to tweet about, either because they were successful or because they needed improvement. Also, we hope that this dataset can identify reasons why people attended the music festival, which could be used for future marketing efforts.

Challenges:

Below are the challanges we faced :​

First being the Streaming API – we were not able use it as coachell was held in april.

Core API - Twitter standard search API only goes back 7-days so running a search for (…, q = ‘coachella’, …) would not work.


Limitations:

AS of now ,We are obtaining data only from one social media platform (ie, twitter), and not across a range of other social media platforms such as facebook and instagram which could also provide good insights.In futher, we would like to obtain the data from the rest .


Implementations and Final Dataset:

Artist LineUp dictionary and Tweet dictionaries are our final datasets.

Artist LineUp dictionary : Scraped pitchfork to create a dictionary of all the artists who performed at Coachella, and their set information.

Tweet Dictionaries:​

Saved tweet objects into json dictionaries broken out by day and sorted by hour.  (For ease of use and distribution, final json files contain only the tweet_ids, not the full tweet objects)​

Provided sample code for retrieving full tweets from specified artist in Artist Lineup Dictionary. ​

Final Dataset and documentation available on Github.

Each '4.XX.19 coachella tweets.json' file is a collection of tweet_id's grouped by hour, with the files separated by date.

Weekend Artist Lineup.json is the set of all artists who performed at coachella with their set information (start time, end time, stage)

Use the 'Retreiving Tweet Dictionary for Coachella Artists' jupyter file as example of how to access the full tweet objects for all tweets sent during a specified artist's set time at Coachella.





