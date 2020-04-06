---
title: "Python Metaclasses"
layout: post
date: 2019-08-20 11:11
tag: [python,metaclasses,generator,decorator,contextmanager]
image: https://procodetech.com/wp-content/uploads/2019/04/python.png
headerImage: true
projects: true
hidden: false # don't count this post in blog pagination
description: "Deep dive into python metaclasses"
category: project
author: danieldiamond
externalLink: false
---
## Deep Dive into Python MetaClasses
Highlights from a great talk by James Powell found [here.](https://www.youtube.com/watch?v=cKPlPJyQrt4)

In this repo you will find notebooks highlighting when and why to use
various metaclasses.
1. [Data Model Methods](https://github.com/danieldiamond/python-metaclasses/blob/master/DataModel.ipynb)
    - Intro to data models
2. [Generators](https://github.com/danieldiamond/python-metaclasses/blob/master/Generators.ipynb)
    - What are generators and when to use them.
    - Eager vs Lazy Loading
3. [Decorators](https://github.com/danieldiamond/python-metaclasses/blob/master/Decorators.ipynb)
    - Investigate runtime objects
4. [Context Managers](https://github.com/danieldiamond/python-metaclasses/blob/master/ContextManagers.ipynb)
    - Putting it all together: combining generators, decorators and context managers

#### NOTE: In python you will always find this pattern:
top-level function or syntax and a corresponding `__method__` function