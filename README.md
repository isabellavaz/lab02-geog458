Lab 02 - Geotagging Tweets
Isabella Vazquez

## Comparison of Two Location Tracking Topics 
# within the U.S and target Country

I decided to run this Tweet crawler on two countries facing immense crisis right now: respectively Ukraine and Palestine. I decided to make this comparison, as I am aware that Ukraine is receivign a lot of attention in the mediascape and I wanted to see what comparable attention was being focused on the crisis in Palestine.

### Visual #1 - Ukraine
I started with running the stream crawler using the location boundaries for Ukraine and the Contiguous United States, including Alaska and Hawaii. (Though only one tweet was geotagged in Alaska for the two latter)
In the search filter I tracked 'Ukraine' and pulled over 100 tweets. Since this is a more recent current event, this made sense for the time. Tweets were pulled for all over the world though and ranged from support for Ukraine to bot tweets that were filling the stream. 

![Map of Tweets filtered 'Ukraine'](lab02-geog458/img/screenshot_of_map-1.png)
Above is the map produced in QGIS that depicts the range of tweets over the globe that streamed from the filter. The pattern depicts a nationwide response from the United States but a concentration in the target country of Ukraine. 

The tweets themselves ranged in context of the ongoing crisis.
Below is the wordcloud generated with some of the content in the tweets.

![Wordcloud for tracked term: Ukraine](img\screenshot_of_wordcloud-1.png)

### Visual #2 - Palestine
The tweets collected under the tracked term 'Palestine' returned a similar amount of tweets suprisingly, however a vast majority had little to nothing to do with the search term itself. I would say that given the time parameters, this contributed to a lot of tweets not being centered on the ongoing conflict in Palestine present day. 
Critiques and observations on the level of media attention differnt countries receive has been brought to the attention of many. And this example suffices as further evidence for that phenomena.

Interestingly, the stream only was able to filter 5 tweets from the Palestinian geography, with the rest of the tweets originating in the Contiguous United States. 

![Map of Tweets filtered 'Palestine'](img\screenshot_of_map-2.png)
Above is the the map that depicts the tweet origins for tracking the term 'Palestine'. I worry though that this filter was incorrect or simply the time parameter no longer relevant because no tweet directly mentioned Palestine. 

![Wordcloud for tracked term: Palestine](img\screenshot_of_wordcloud-2.png)
The context in this world cloud is far more skewed than that of Ukraine. I think again this has to do with the time relevance between the two search terms and the more prevelant attention on the ongoing war in Ukraine. 
