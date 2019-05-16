---
title: "Wine Predictions Based on Sommelier Reviews (NLP with a ULMFit Network)"
layout: post
date: 2018-09-12 12:51
tag: [deeplearning,nlp,ulmfit,transferlearning,rnn]
image:
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Wine Predictions Using an ULMFiT Architecture with Transfer Learning"
category: project
author: danieldiamond
externalLink: false
---

![ulmfit](/assets/images/ulmfit.png)
<i>Image source: [ULMFiT paper by Jeremy Howard and Sebastian Ruder](https://arxiv.org/pdf/1801.06146.pdf)</i>

Using PyTorch and Deep Learning applications in NLP, [this project](https://github.com/danieldiamond/nlp-projects/tree/master/wine-reviews) implements a ULMFit network to incorporate transfer learning in an NLP framework to predict the type of wine from a Sommelier review.

The RNN model utilizes transfer learning from the WT103 pretrained language model and was then further trained on a dataset scraped from WineEnthusiast on November 22nd, 2017.
