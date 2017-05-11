# What is this supposed to do? #
* VisaInterviewSlackBot is a automated bot, with which f1 visa aspirants can chat with. This should be like a VO (visa officer), who finally signs your passport or rejects it. The user is supposed to type in the answers to the questions asked, VisaInterviewSlackBot is supposed to predict the probability that the students visa interview would be accepted.

# Plan in brief? #

1. VisaInterview  should be accessed via [Slack](https://slack.com) which is a popular chat application with facility for api integrations. Students hence must have a slack account to interact with VisaInterviewSlackBot.
2. VisaInterviewSlackBot should be fed in with the data from various websites, which are related to similar topic.. ie., questions and correct answer to those questions Ex: happyschools.com, usvisatalk.com etc. This should be VisaInterviewSlackBot's training data. VisaInterviewSlackBot should learn the correct answer for every question which it will be asking.
3. VisaInterviewSlackBot should iteratively keep learning from the answers which the users are giving. If a particular answer is real good, it should flag it and learn from it *[How? I dont know that as of now. Also learning from the data which VisaInterviewSlackBot itself classified as good, is a good idea or not.. i dont know that as well as of now.]*
4. VisaInterviewSlackBot should calculate the probability of closeness of the students answer to all the correct and wrong answers, and figure the degree of truth. Overall interview's review is the overall product of probabilities of the answers which the user has provided *(May be a good evaluation criteria..requires more thought)*. So rather than performing really good per question, user must perform really good overall as well.
5. VisaInterviewSlackBot should online parse various websites and keep indexing the correct answers from whichever websites are deemed to be the source of correct data.


# Instructions to Execute?
1. pip install slackbot
2. clone the respository to some directory
3. add path to slackbot_setting.py to system PATH variable
4. cd to the project directory and run 'python run.py'
5. this should start the bot without erros
6. Login to channel and chat with vo user!!


![Untitled Diagram.png](https://github.com/codelibra/VisaInterviewSlackBot/blob/master/plan.png)
