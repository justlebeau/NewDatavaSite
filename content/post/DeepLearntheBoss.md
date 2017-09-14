---
title: "Deep Learning and The Boss"
date: 2017-03-24
tags: ["R", "deeplearning", "rstats", "RNN", "neural networks"]
---

I created a Twitter account which was inspired by a couple Twitter accounts that applied a particular type of machine learning technique to learn how two (at the time) presidential hopefuls spoke. I thought, why not see what a model like this could do with lyrics from my favorite rock n roll artist?

Long short term memory (LSTM) is a recurrent neural network (RNN) that can be used to produce sentences or phrases by learning from text. A twitter account that inspired this [@deeplearnbruce](https://twitter.com/deeplearnbern) was [@deeplearnthebern](https://www.twitter.com/deepdrumpf) which use this technique to produce phrases and sentences.

I scraped a little more than 300 of his songs and have fed them to a LSTM model using R and the mxnet library. Primarily I used [mxnet](http://mxnet.io/) to build and train the model…great site and tools. &nbsp;The tutorials on their site are very helpful and particularly [this one](http://mxnet.io/tutorials/r/charRnnModel.html)


![First tweet](static/img/bosstwitter1.png)


The repository is [here](https://github.com/justlebeau/justlebeau.github.io/tree/master/brucebot).  Follow [him here](https://twitter.com/DeepLearn_Bruce) for tweets that are hopefully entertaining for Springsteen fans or anyone else.
