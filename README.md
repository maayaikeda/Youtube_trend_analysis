# Youtube_trend_analysis

Videos that are on YouTube trending page changes every day and it is a reflection of what is happening in the world and the popular topics people are discussing at the time. At the time of this analysis, democratic and republican national convention just happened and the trailer for the new Batman movie was released.

I analyzed data from 4 English speaking countries (US, Australia, Canada, Great Britan) in detail to see what kinds of videos and channels are trending at this time (08/26/2020-09/04/2020). 

The analysis gives us insights into how to publish videos on YouTube to go on the trending page.

Majority (58.5%) of all trending videos were in Entertainment, music, or sports. 

To understand what kinds of videos trend on YouTube, I took a look at the what words were used in the tags and titles in trending videos of all categories across days I collected data from. This is the word cloud from the whole dataset. Since it does not give clear picture of what kinds of videos are trending, I decided to look at videos of each category and individual days separately.
I first took on the first day I collected data (8/26/2020). The word cloud shows that frequently used words are related to the Republican National Convention that was held on 8/24/2020-8/27/2020. Six videos out of 16 videos trending in the ‘News and Politics’ category were related to the Republican National Convention. Only two of those were also tagged Democratic National Convention which was held 8/17-8/20. To see if the number of videos is a reflection of the public interest on the topics, I looked for google interest over time for the search ‘Republican National Convention’ and ‘Democratic National Convention’. The plot shows when the interests peaked vs when the videos were published for videos started trending after 8/26/20.
This is the plot for when the videos were published vs when they were on the trending page. 
Hurricane Laura was approaching Texas on the 27th, and the word cloud for the ‘News and Politics’ category shows that frequently used words are related to Hurricane Laura and less words are used related to the political conventions.

For the Entertainment category, many videos with the word “trailer” and “Batman” in the titles or tags were trending. The interest for both the word “trailer” and “Batman” on googled peaked around 8/22 and 8/23/20. While not all trending videos tagged or titled with the word “trailer” were related to the new Batman movie trailer released on 8/22/20, many of them were. Even though the suicide squad movie trailer was also trending on 8/26, there were a lot less than videos related to the suicide squad movie trailer. This reflects the difference in the amount of interest on google search. While the search for “suicide squad does peak at the same time as “Batman,” the peak is a lot smaller than “Batman.”
Interestingly, 12 videos with the word “trailer” were still trending on 09/08 but none were related to the batman movie. 

Therefore, many videos that eventually go on the trending page is uploaded exactly when the interest in the google search peaks and go on the trending page a couple of days later (average lab between publish date to trending date was 3 days). Videos in the entertainment category trended longer (average 4.2 days) than videos in the News and Politics category (4.6 days) (t-test, p = 0.0058).


To support these observations, I tested to see if the number of trending videos tagging a certain word is correlated with the google interest score. When tested for frequently tagged words (>10) in trending videos (other than ‘2020’ and ‘videos’), the sum of Google interest index score 3 days prior significantly correlated to the number of videos with those words in the title or tag (Pearson, p = 0.028). 

However, when I performed the same test for top trending words on Google, there were no relationship between the amount of interest on Google and the number of videos made on the topics 1-6 days later. This shows that just using words that are high on Google search ranking is not enough for videos to trend. This makes sense, since not all words/phrases searched on Google are interesting as video topics. Together, among words that are used 

What kind of channels produce multiple trending videos?
As expected, most channels with multiple trending videos were by large cooperation such as “Entertainment tonight” and “MTV.”
Also as expected, some of the channels were ran with single individuals with large followings (James Charles and Emma Chamberlain, 21M and 9M subscribers respectively). While James Charles includes words and people’s names of high interest in his video titles and tags, Emma Chamberlain only tags herself and many of her videos still trend. We can assume that fans of these channels rush to see their content as soon as they upload new videos and their channel title/their names themselves are high interest on google. One the other hand, some of channels with the many trending videos on the days of this research were small (less than 2M subscribers. For instance, the channel “The United Stand” only have 800k subscribers and only 300k or less views for their videos but consistently have trending videos on across many days. This channel covers information on the English football team “Manchester United,” and the interest on google for Manchester united is very across all the days. 
To get more clue about the relationship between search term interest and videos trending, I looked at two other small channels with more than two trending videos (Dani and SaffronBarkerVlogs). While Dani’s channel is small, google search interest for ‘Dani’ is high. ‘SaffronBarkerVlogs’ is not high in interest on google but the videos trended from this channel used words such as “dream house”, “road trip” and “boyfriends” that had high interest score on google. YouTube suggest videos related to videos users are currently watching, having a title similar to one of James Charles ‘s videos at the same time could have helped SaffronBarkerVlogs’ video trend. 

Overall, this analysis suggests that to get videos on the YouTube trending page, it helps to 
1.	Publish the video from a large channel 
2.	Create the video on a topic (or person) that are high in interest on Google
Examples include, popular sports team, influencers with over 5M followers, controversial topics and movie trailers
3.	If the video is on a topic that is related to a news story or movie, upload the video as soon as the story breaks.
4.	Create content similar to other popular videos 



