## 1. Introduction
- Show the statistical numbers of FPT's channels (subscribers, views, likes, comments...)
- Identify the relationship between total views vs total likes and total views vs total comments.
- Show the view distribution per channel, video duration, upload schedule and word cloud with video title. Answer the question: "How to improvve video perfomance?" 

## 2. Methodology 
- Data Collection
  - Crawl data from Youtube API.  
- Data Wrangling
  - Cleaning data (changing data type, resolving null values...)
- Identify the relationship between the metrics using heatmap chart.
- Create a dashboard per channel using Power BI 

[View](https://github.com/huyvofjh/FptChannelAnalysis/blob/main/FPTChannelsAnalysis.ipynb) to get details.

 ## 3. Data Visualization  
  
![channel](https://user-images.githubusercontent.com/88859966/211520086-dfa51638-da9f-4aeb-8e06-984a8cf99287.jpg)
- FPT has 7 channels. Total subscribers, total videos and total views are 2.6M, 7685 and 1.1B respectively until 10/01/2023
- The football channels (FPT Bong Da and FPT Bong Da Viet) ranked first and second in subscribers and views. 
- F Drama ranked third in subscribers but the total views of this channel is only 2.3M (lowest in the view list) 
- The positive correlation between total views vs total subscribers and total views vs total video. 
=> The channels which produce a lot of videos and have a lot of subscribers have a large number of views.


![bongda](https://user-images.githubusercontent.com/88859966/211520577-fb6e64bc-22a4-422b-a6d0-ba4b9335f5de.jpg)
- The channel whose has the most subsribers and views is FPT Bong Da. The statiscal numbers are 925K subscribers, 486M views, 3.7M likes and 334K comments.
- The channel has 2444 videos. 
- The view distribution per video is around 350K - 500K.
- Most videos are around 15 minutes. 
- FPT Bong Da usually uploads video 3 times a week (Tuesday, Wednesday and Thursday - the time which Champions League and Europa League happens)
- The positive correlation between total views vs total likes and total views vs total comments.
=> The more people who watch the videos the more likes and comments. 
- According to word cloud chart, the main content on this channel is the highlight of UEFA League's matches (Champions League and Europa League)


![bongdaviet](https://user-images.githubusercontent.com/88859966/211520676-7b850837-a51e-4f3a-af94-dc38632fefe7.jpg)
- Total subsribers, total views, total likes and total comments are 841K, 366M, 2.1M and 98K respectively. 
- The channel has 2138 videos. 
- The view distribution per video is around 200K - 350K.
- Most videos are around 15 minutes. 
- FPT Bong Da Viet usually uploads video on Tuesday and Thursday. 
- In general the more people who watch the videos the more likes and comments.
- According to word cloud chart, the main content on this channel is Vietnam Football, U23 and AFC Cup. 


![fdrama](https://user-images.githubusercontent.com/88859966/211520806-93b985d3-79e0-43d7-98aa-5c43cafa6214.jpg)
- The statiscal numbers are 332K subscribers, 2.3M views, 28K likes and 1467 comments. 
- The channel has 137 videos. 
- The view distribution per video is less than 100K.
- Most videos are around 7-10 minutes. 
- F Drama usually uploads video on Tuesday, Thursday and Sunday. 
- In general the more people who watch the videos the more likes and comments.
- According to word cloud chart, the main content on this channel is drama about school,student. Especially the channel focuses on producing short video. 


![fsports](https://user-images.githubusercontent.com/88859966/211520890-b4f194b1-38e5-47f0-b8e6-6a7cceaa5e07.jpg)
- The statiscal numbers are 202K subscribers, 115.3M views, 585K likes and 36K comments. 
- The channel has 1355 videos. 
- The view distribution per video is around 150K - 250K.
- Most videos are under 15 minutes. 
- F Sport usually uploads video on Saturday, Tuesday and Thursday. 
- In general the more people who watch the videos the more likes and comments.
- According to word cloud chart, the word "Chuyển Động" usually appears in the title of videos. The main content are sports, U23 Vietnam...


![fcine](https://user-images.githubusercontent.com/88859966/211520970-62ac07fb-63b9-4351-b8a4-8864f2961d80.jpg)
- The statiscal numbers are 117K subscribers, 22.2M views, 140K likes and 12K comments.
- The channel has 334 videos
- The view distribution per video is around 50K - 150K.
- Most videos are around 40 minutes. 
- F Cine uploads regularly everyday of the week, especially Wednesday.  
- In general the more people who watch the videos the more likes and comments.
- According to word cloud chart, the main content on this channel is is series movie of China.


![fmusic](https://user-images.githubusercontent.com/88859966/211521101-e7f6bcb0-ec92-4f41-ae66-3989823d49b1.jpg)
- The statiscal numbers are 116K subscribers, 66.9M views, 565K likes and 31K comments. 
- The channel has 531 videos. 
- The view distribution per video is around 100K - 200K.
- Most videos are under 10 minutes. 
- F Music usually uploads video on Monday, Tuesday and Wednesday. 
- In general the more people who watch the videos the more likes and comments.
- According to word cloud chart, the main content on this channel is show "Giao Lo Thoi Gian", the songs which is sung live and the channel focuses on producing short videos. 


![fgiaitri](https://user-images.githubusercontent.com/88859966/211521113-7f55ecb5-6ab0-41e6-bfb8-d1f7aab20a57.jpg)
- The statiscal numbers are 55K subscribers, 6.9M views, 83.4K likes and 4196 comments.
- The channel has 746 videos
- The view distribution per video is lower 100K.
- Most videos are under 10 minutes. 
- F Giai Tri usually uploads video on days of week from Monday to Friday  
- In general the more people who watch the videos the more likes and comments.
- According to word cloud chart, the words "Ngôi Sao", "30s", "ĐCTK" usually appears in the title of videos. The channel also focuses on producing short videos. 
