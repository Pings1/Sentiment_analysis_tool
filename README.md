# Sentiment_analysis_tool
Hi ! 
This is the sentiment analysis tool, which will help you to understand the sentiment of the feedback(for example).              
how it works in my case:
1)I have the .xls file with feedbacks (it could be any type of file , for example .csv) .
2)Script reads all feedbacks from "feedback" column and drops the rows without the feedback.
3)With the help of indicoio library we anylyze the sentiment , output will be the list with 5 parameters:('anger','fear','joy','sadness','surprise')
4)library grades the sentiment by 5 parameters which are shown above.
5)As a result we see the radar plot which shows which emotion is more outstanding and which is lee outstanding.
6)You can choose which type of output you want. All feedbacks shown on one radar plot , or the quantile of all feedbacks. 
