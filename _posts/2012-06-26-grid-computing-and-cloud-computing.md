---
layout: post
title: "Grid computing and Cloud computing"
description: ""
category: tech
tags: [computing, research]
---
{% include JB/setup %}

即将从一个EEer转成了CSer了，由于非科班出身，底子还是单薄了点，所以略做了一下功课。

###[Cloud computing][1]
From wiki，

>Cloud computing is the delivery of computing and storage capacity as a service to a heterogeneous community of end-recipients.

正如所言，Cloud computing是一种提供计算和存储的服务。那么，它是怎样提供服务的？

>Cloud computing incorporates infrastructure as a service (IaaS), platform as a service (PaaS) and software as a service (SaaS) as well as Web 2.0.

如此一来，开发人员不需要再去购买、配置、维护硬件设备和软件环境，他们只需要将应用交付到提供云计算的服务商，然后通过应用所占用的计算和储存资源进行付费。因此，云计算的兴起减少了开发、维护成本，降低了互联网创业门槛，极大的促进了中小型互联网公司的发展。（同学们，弹起你手中的键盘，创业吧！）

有名的服务商有如下几个：

- **Amazon Web Services (AWS)** – AWS delivers a set of services that together form a reliable, scalable platform ‘in the cloud’. These pay-as-you-use cloud computing services include Amazon S3, Amazon EC2, Amazon SimpleDB, Amazon SQS, Amazon FPS, and others.

- **Salesforce.com** – Delivers businesses over the internet using the software as a service model.

- **Google Apps** - Software-as-a-service for business email, information sharing and security.

- **Heroku** - Heroku (pronounced her-OH-koo) is a cloud application platform – a new way of building and deploying web apps.


###[Grid computing][3]

>Grid computing is a form of [**distributed computing**][4] whereby resources of many computers in a network is used at the same time, to solve a single problem. Grid systems are designed for collaborative sharing of resources. It can also be thought of as distributed and large-scale cluster computing.

Grid computing不是作为一个商业服务存在，而更多的是应用在科学计算中。它主要目的通过网络共享计算、储存资源来解决一些大规模问题。插一句闲话，云计算感觉像大家分别把各自的东西送到一个地方加工处理，而网格计算有点像把一个大东西分给大家处理，处理好了再还回去。

>Grid computing is making big contributions to scientific research, helping scientists around the world to analyze and store massive amounts of data by sharing computing resources.

那么，网格计算与其他分布式计算有什么区别？

>What distinguishes grid computing from conventional high performance computing systems such as cluster computing is that grids tend to be more **loosely coupled**, **heterogeneous**, and **geographically dispersed**.

顺便提一下，分布式计算在科学计算的应用主要有：[**cluster computing**][5] and various [**volunteer computing**][6] projects.

Grid computing是如何处理异构的？Cloud computing, distributed computing, grid computing之间有着怎样千丝万缕的关系？背后支撑它们的理论、算法是什么？

预知后事如何，待我继续research！

[1]:http://en.wikipedia.org/wiki/Cloud_computing
[3]:http://en.wikipedia.org/wiki/Grid_computing
[4]:http://en.wikipedia.org/wiki/Distributed_computing
[5]:http://en.wikipedia.org/wiki/Cluster_computing
[6]:http://en.wikipedia.org/wiki/Volunteer_computing