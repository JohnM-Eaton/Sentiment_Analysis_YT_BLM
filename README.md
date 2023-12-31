# Sentiment_Analysis on YouTube Videos featuring BLM 2020

In the aftermath of George Floyd’s death, multiple peaceful protests and violent riots occurred across various American cities. I wrote a paper to examine the various sentiments individuals have regarding these protests and riots. Specifically, did these protests sparked support for the Black Lives Matter cause? Or have they renewed support among individuals for police officers? To explore this subject, comment data were gathered from ten of the most highly viewed YouTube videos featuring footage of the protests. A sentiment analysis of these comments revealed more positive sentiments and emotions regarding the police and white people in general than the black cause. 

The data were acquired using the R package ‘tuber’ version 0.9.9 (Gaurav, 2019). A breakdown of these videos including the channel under which they were posted, the date they were posted, the title of the video, and the number of views, likes, dislikes, and comments they received is in Table 1. Table 1 reflects the statistics all videos as of July 16th, 2020, which is the date the data were collected. These videos were specifically chosen because they had the most views out of any videos covering the same incidents. There are a total of seven channels the videos were taken from. 

![](https://github.com/JohnM-Eaton/Sentiment_Analysis_YT_BLM/blob/main/Table1.svg)

As seen in Figure 1, which denotes the number of word sentiments and emotions for all comments from all videos, it appears as though the sentiments and emotions skew slightly negative.  In a separate analysis, this overall trend continued; there was no significant variation in sentiment for comments when comparing across channels. 

![](https://github.com/JohnM-Eaton/Sentiment_Analysis_YT_BLM/blob/main/Figure%201.png)

Figure 2 shows a breakdown of each sentiment and emotion by the top ten words in each category. Here, one can see a clearer picture of where the comment sentiments lie. The number one word associated with the “positive” sentiment and “trust” emotion is “police.” Likewise, the second most word associated with “positive” and “trust” and the number one word associated with “joy” and “anticipation” is “white.” Curiously, there is also a recurrence of the word “god,” which has top spots in “positive”, “joy”, “trust”, “anticipation”, and “fear”. Also telling, is the absence of references to President Trump in negative sentiment/emotions. Yet, the president does appear in the “positive”, “surprise”, and “trust” sentiment/emotions. In summary, the positive sentiment/emotions favors the police, whites, God, and Trump. 
![](https://github.com/JohnM-Eaton/Sentiment_Analysis_YT_BLM/blob/main/Figure%202.png)
