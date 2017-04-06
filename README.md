# Promoting Positive Climate Change Conversations via Twitter

This repository contains the code, network visualizations, and slides I created for my final project of the Metis Data Science program. My project is an exploration of the conversations about climate change that took place on Twitter in March 2017.

![Twitter network with communities and influential users](media/network_with_names.png)

**Analysis**  
With 1 million tweets from 560,000 users, I was able to identify users as belonging to different communities, such as Journalists, Canadian Politicians, or climate change Deniers. Topic modeling showed that each community has a unique set of topics that they talked about, and sentiment analysis showed that different communities felt differently about the same topics. Lastly, I identified some users whose sentiment differed from their community at large - for example, conservative members of the climate change Denier community who actually do accept climate change science.

**Tools:**  
For this project I used Tweepy and the Twitter API to pull tweets. I used Pyspark running on an AWS instance for tweet preprocessing and model building. I used NetworkX and Gephi for network analysis and visualization.

**The files:**  
The Jupyter notebooks for this analysis are listed in order above. Note that notebooks 3 and 4 are extra - I built a naive bayes model and an SVM model to predict a user's climate change acceptance from their tweets. The best model was about 59% accurate, but wasn't useful enough for further work.

The **Network Graphs** folder contains .gephi files.  
**Media** contains some visualizations of the strongly connected component of the Twitter network.  
Lastly, the slides for my project presentation are [here.](https://docs.google.com/presentation/d/14U2FqCU0eeWo3hG4r8b7OaYqbUzZEov3EKTsAbXQFGE/edit?usp=sharing)
