With about 190 million users communicating 65 million tweets a day, Twitter has proven to be a huge social hub on the internet. The philosophy behind Twitter is to allow users to share their thoughts and feelings with the rest of the world, while giving them a chance to read the thoughts and feelings of any one. Twitter is solely based on the concept of communication via short text messages or tweets, which has enabled its users to drop their inhibitions about security and privacy. Thus, most of these messages or tweets tend to reflect the user’s real thoughts and opinions. With the staggering number of tweets that each user posts every day, it might be possible to understand and analyze the topics of interest for the user.

With millions of news stories coming up on the internet each day, it becomes hard to separate the news that an internet user wants to read and the news that he/she does not want to read. Personalization of news would eliminate this dilemma by providing the user the news that he would love to read. And to determine what news the user would love to read, we could learn and understand his/her interests using the activity on his/her twitter profile as explained above.

In this project, we propose to do the following :

1. Use the Twitter Streaming API to obtain real time information on twitter users and their tweets.

2. Develop a model of ‘interest’ identification using the following  criteria :

> a. Text mining on the user’s tweets to isolate keywords that may point to his/her interest areas. (For example, if a user tweets that “I hope that India wins the cricket            world cup”, we know that the user is interested in cricket and would love to read news about the same.)

> b. Extracting the hash-tags used by the user in his/her tweets. (For example, if the user tweets, “The president of #Egypt must step down”, we know that the user is                 interested about the revolution in Egypt and love to read news about it.)

> c. Identifying the users that our subject follows (For example, if the user follows ‘Natalie Portman’, the user might be interested in reading news stories about the            actress’ upcoming movies)

3. Crawling through news websites and extracting news information relevant to the interests of the user which was identified previously.
4. Categorizing and ranking the personalized news results.
(If time permits, this analysis could also lead to certain socio-political analytics such as the trends in various events, their popularity etc.)