# Youtube_trend_analysis



Videos that are on YouTube trending page changes every day and it is a reflection of what is happening in the world and the popular topics people are discussing at the time. At the time of this analysis, democratic and republican national convention just happened and the trailer for the new Batman movie was released.

I analyzed data from 4 English speaking countries (US, Australia, Canada, Great Britan) in detail to see what kinds of videos and channels are trending at this time (08/26/2020-09/04/2020). 

The analysis gives us insights into how to publish videos on YouTube to go on the trending page.

Majority (58.5%) of all trending videos were in Entertainment, music, or sports. 

![categories](/images/categories.png)


To understand what kinds of videos trend on YouTube, I took a look at the words were used in the tags and titles in trending videos of all categories across days I collected data from. This is the word cloud from the whole dataset. 

![wordcloudall](/images/wordcloudall.png)

As you can see, it does not give clear picture of what kinds of videos are trending. Therefore, I decided to look at videos of each category and individual days separately.

## 'News and Politics' Category
I first took on the first day I collected data (8/26/2020). 

![worldcloudn26](/images/wordcloudnews26.png)

The word cloud shows that frequently used words are related to the Republican National Convention that was held on a couple of days prior (8/24/2020-8/27/2020). Six videos out of 16 videos trending in the ‘News and Politics’ category were related to the Republican National Convention. 

![conventionvideos](/images/Screen%20Shot%202020-09-09%20at%2012.58.03%20PM.png)

Only two of those were also tagged Democratic National Convention which was held much longer ago (8/17-8/20), suggesting that the topics of trending videos reflects what is on the news and changes in people's interests.
The next day (8/27/20), the word cloud looked very different.

![worldcloudn27](/images/wordcloudnews27.png)

 Hurricane Laura was approaching Texas on the 27th, and words related to Hurricane Laura are top words used as titles and tags. This may relect the shift in public's interest from the Republican National Convention to Hurricane Laura.

 To see if the number of videos is a reflection of the public interest on the topics, I looked for google interest over time for the search ‘Republican National Convention’, ‘Democratic National Convention’, and 'Hurricane Laura', and compared it with the timing of when the trending videos were published. 

![politicsinterest](/images/publishedvsinterestnews.png)


For videos started trending after 8/26/20, video uploads peaked either at the same time or soon after the interest peaked. I also compared the day the videos were on the trending page vs. when the videos were published. 

![politics](/images/politicsdr.png)

The figures shows that the videos were published soon after the interest for the words peaked while those videos did not get on the trending page until a couple of days later. 

## 'Entertainment' Category

For the Entertainment category, many videos with the word “trailer” and “Batman” in the titles or tags were trending on 8/26/20. 

![ewordcloud26](/images/wordcloudentertainment26.png)

And the word could for the next day and the 3 days later (8/29/20) still looked similar. In addition, most of these videos are related to the new Batman traile released more than 4 days prior (on 8/22/20).



![trailervideos](/images/Screen%20Shot%202020-09-09%20at%201.00.51%20PM.png)



This suggests that the videos entertainment category trend longer than the videos in the News and Politics category. Indeed, videos in the entertainment category trended longer (average 4.2 days) than videos in the News and Politics category (4.6 days) (t-test, p = 0.0058). The longest time period a video was trending was 11 days for this data set.

![trailerinterest](/images/trailerinterest.png)

![bosemansuicideinterest](/images/bosemansuicideinterest.png)



Even though the suicide squad movie trailer was also released on 8/22/20 and was trending on 8/26, there were a lot less than videos related to the suicide squad movie trailer. This reflects the difference in the amount of interest on google search. While the search for “suicide squad does peak at the same time as “Batman,” the peak is a lot smaller than “Batman.”
Interestingly, 12 videos with the word “trailer” were still trending on 09/08 but none were related to the batman movie. 


![enterainmentinterestvspublishedpng](/images/enterainmentinterestvspublished.png)


For each key word, the peaks of trending videos are published is almost the same as the peaks of Google interest. In other words, many videos that eventually go on the trending page is uploaded exactly when the interest in the google search peaks and go on the trending page a couple of days later (average lab between publish date to trending date was 3 days). 



To support these observations, I tested to see if the number of trending videos tagging a certain word is correlated with the google interest score. When tested for frequently tagged words (>10) in trending videos (other than ‘2020’ and ‘videos’), the sum of Google interest index score 3 days prior significantly correlated to the number of videos with those words in the title or tag (Pearson, p = 0.028). 

![interstvstrend](/images/interstvstrend.png)

However, when I performed the same test for top trending words on Google, there were no relationship between the amount of interest on Google and the number of videos made on the topics 1-6 days later. This shows that just using words that are high on Google search ranking is not enough for videos to trend. This makes sense, since not all words/phrases searched on Google are interesting as video topics. Together, among words that are used 

![cyrusscatter](/images/cyrusscatter.png)


What kind of channels produce multiple trending videos?
As expected, most channels with multiple trending videos were by large cooperation such as “Entertainment tonight” and “MTV.”

Channels with multiple trending videos in the Entertainment category.

![entertainmentchannels](/images/entertainmentchannels.png)


Also as expected, some of the channels were ran with single individuals with large followings (James Charles and Emma Chamberlain, 21M and 9M subscribers respectively). While James Charles includes words and people’s names of high interest in his video titles and tags, Emma Chamberlain only tags herself and many of her videos still trend. We can assume that fans of these channels rush to see their content as soon as they upload new videos and their channel title/their names themselves are high interest on google. One the other hand, some of channels with the many trending videos on the days of this research were small (less than 2M subscribers. For instance, the channel “The United Stand” only have 800k subscribers and only 300k or less views for their videos but consistently have trending videos on across many days. This channel covers information on the English football team “Manchester United,” and the interest on google for Manchester united is very across all the days. 

![youtubersinterest](/images/youtubersinterest.png)



To get more clue about the relationship between search term interest and videos trending, I looked at two other small channels with more than two trending videos (Dani and SaffronBarkerVlogs). While Dani’s channel is small, google search interest for ‘Dani’ is high. ‘SaffronBarkerVlogs’ is not high in interest on google but the videos trended from this channel used words such as “dream house”, “road trip” and “boyfriends” that had high interest score on google. YouTube suggest videos related to videos users are currently watching, having a title similar to one of James Charles ‘s videos at the same time could have helped SaffronBarkerVlogs’ video trend. 


![jamescharles](/images/Screen%20Shot%202020-09-09%20at%201.29.33%20PM.png)
![emma](/images/Screen%20Shot%202020-09-09%20at%201.29.45%20PM.png)
![saffron](/images/Screen%20Shot%202020-09-09%20at%201.29.52%20PM.png)


![wordsinterests](/images/wordsinterests.png)


Overall, this analysis suggests that to get videos on the YouTube trending page, it helps to 
1.	Publish the video from a large channel 
2.	Create the video on a topic (or person) that are high in interest on Google
Examples include, popular sports team, influencers with over 5M followers, controversial topics and movie trailers
3.	If the video is on a topic that is related to a news story or movie, upload the video as soon as the story breaks.
4.	Create content similar to other popular videos 



