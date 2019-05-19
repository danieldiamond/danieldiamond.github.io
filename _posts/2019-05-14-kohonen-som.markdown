---
title: "Kohonen Self Organizing Map (SOM)"
layout: post
date: 2019-05-14 12:51
tag: [kohonen,SOM,clustering,dataviz]
image: http://www.pitt.edu/~is2470pb/Spring05/FinalProjects/Group1a/tutorial/kohonen1.gif
headerImage: true
projects: true
hidden: false # don't count this post in blog pagination
description: "Implementation of a Kohonen Self Organizing Map (SOM)"
category: project
author: danieldiamond
externalLink: false
---

![som](../assets/images/som.gif)


[This project](https://github.com/danieldiamond/kohonen-network) implements Kohonen Self Organizing Map (SOM) and trains the network whilst investigating the effects of initial hyperparameter settings.

The Kohonen SOM provides a data visualization technique which helps to understand high dimensional data by reducing the dimensions of data to a map. SOM also represents clustering concept by grouping similar data together.

Unlike other learning technique in neural networks, training a SOM requires no target vector. A SOM learns to classify the training data without any external supervision.

Within this notebook, several concepts are discussed, from algorithm complexity and speed, to hyperparameter sensitivity analysis as shown below:
![som](../assets/images/som_sensitivity.png)
