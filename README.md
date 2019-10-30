# Team Government
Social networks are being used by illegal or activist organizations to distribute messages with the intention of influencing people and recruiting new members. 
Social media is playing a very important role in the way people think. When accurately targeted, repeated messages can reinforce political ideas or even flip the way of thinking of the most indecisive.
In this regard, TU_hackers has been identified as one of the movements that relies the most on social networks to spread propaganda and try to influence the public opinion. 
Social networks are also used by terrorist organizations as a tool for recruiting new members. Sentiment analysis to detect radicalization has been applied to social networks in the past as an evolution of previous analysis that were traditionally focused on websites and forums. The problem of nodes that play an important role as influencers or that spread propaganda and the way in which it is propagated is a growing area of research.

Your taskforce has continuously tagged activists by their communication patterns and subsequently tracked them down using the government surveillance camera system. Unfortunately, your team's security has been lacking. Not only has one model been stolen a while ago, a backdoor for testing messages on your current model was established by the TU_hackers. While those two incidents constitue a major backfall in your agenda, the backdoor might give you insights into the activists communication patterns.

# Task
Create a model that successfully separates activist messages from messages by the general public.

# Resources
* Your team has collected several examples of activists' blog posts and messages as a baseline. 
* To detect messages exchanged by members of the general public you can use samples from the sqlite database storing one million posts from the [derstandard.at forum ](https://github.com/OFAI/million-post-corpus/releases/download/v1.0.0/million_post_corpus.tar.bz2).
* Backdoor Logging Screen

# Hints
* You can follow the same steps as in stage 1
* See if you can find more data online.
* Pay attention to class imbalance.
* Look at different vectorizers
* Look for different algorithms suitable for text classification.

# Deliverables
* a `model.pkl` file that can be loaded to assign textual input to a class `activist` or `public`
