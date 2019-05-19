---
title: "Super Resolution Using GANs and U-Nets"
layout: post
date: 2018-10-11 12:51
tag: [deeplearning,GAN,unet,cv,cnn]
image:
headerImage: false
projects: true
hidden: false # don't count this post in blog pagination
description: "Using U-Nets To Enhance Image Resolution"
category: project
author: danieldiamond
externalLink: false
---

<img src="https://raw.githubusercontent.com/danieldiamond/dl-projects/master/super-resolution/images/dog_lr.png" width="200" height="200" align="left" />
<img src="https://raw.githubusercontent.com/danieldiamond/dl-projects/master/super-resolution/images/dog_hr.png" width="200" height="200" align="right" />
<br><br><br><br><br><br><br><br>

Using PyTorch and Deep Learning applications to increase the resolution of images.

First approach is using Generative adversarial networks (GANs). GAN approach uses a loss function, which calls another model to decide "Is this a high res image or a low res image"

[This project](https://danieldiamond.github.io/dl-projects/) is then improved using U-Nets and Feature Loss Applications inspired by the paper ["Perceptual Losses for Real-Time Style Transfer and Super-Resolution"](https://arxiv.org/pdf/1603.08155.pdf) by Johnson et al. Instead of using MSELoss on pixel values and a CrossEntropy loss for the Critic model, we compare features displayed in the real image and the generated image.

<img src="https://raw.githubusercontent.com/danieldiamond/dl-projects/66cc8ddb1578bc56ca9ad34f7e2c269bbcac87b7/super-resolution/images/perc.png" />
<i>Johnson, et al. “Perceptual Losses for Real-Time Style Transfer and Super-Resolution.” Computer Vision – ECCV 2016 Lecture Notes in Computer Science, 2016, pp. 694–711.</i>
