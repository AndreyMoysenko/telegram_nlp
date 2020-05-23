# NLP ON MESSANGER  

## Background
I have noticed that was wasting too much time on reading tons of messages in telegram chats worrying to miss something useful. E.g. I have a chat with other people living in my house about some problems, solutions and joint ventures, producing over 300 messages a day. 

So I decided to apply a little machine learning to this problem in order to save time and still be aware of problems being discussed in useful chats.


[![Scheme](https://i.ibb.co/6swP3VN/nlp-route.png)](https://i.ibb.co/6swP3VN/nlp-route.png)


1. Parse telegram
2. Text analytics

**`Fails:`**  
- `At first I used options provided by Telegram desktop to download data, but it takes a day to be approved and is downloaded in not very useful format`
- `I tried LDA for text modeling, but it didn't fit well enough with the task`
- `TSNE to look at 300-d vectors in 2-d was a bad idea - just a mess`
- `KNN approach was to slow, not approved. HDBScan showed to be not relevant for the task. KMeans - too simplified`
