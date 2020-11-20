---

title: "Lambda Architecture: Big Data Processing"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-11-19T23:36:20-03:00
lastmod: 2020-11-19T23:36:20-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## Introduction
In this post I want to introduce a data-processing architecture known as Lambda.
This is useful for any business wanting to kick-start their journey on advanced
analytics and before making grow the Data Science team, make sure a solid data
platform is put in place with strong engineering foundations.

I will explain what a lambda architecture consists of and why it is needed in the context
of big data and real-time analytics. Secondly I'll show the benefits of implementing
this architecture and what sort of questions you can answer from a business point of view.
Lastly, I will display what an implementation would look like in AWS and three use-cases
that will boost the efficiency of your business through data.

## What is lambda architecture?


Let's take a look at the definition by Wikipedia:

> Lambda architecture is a data-processing architecture designed to handle massive 
> quantities of data by taking advantage of both batch and stream-processing methods.

It is a way to build applications that can handle massive quantities of data by loading
it into an immutable source truth (*infinite storage*) which is then furthered processed 
and post-consumed by two layers that can act independently, either on a batch or on a 
stream fashion. This is extremely powerful for real-time analytics and AI implementations 
and can drive automation for human-centered activities.

A key concept here is the concept of events; every data point that is produced for, and/or 
in the platform, it is treated as a timestamped event which (can) trigger
any type of operation or procedure defined in the system - at the method required.

In order to cope with the infrastructure needed - latency, throughput, and fault-tolerance - 
for the batch as well as for the real-time data processing, we can base our implementations
on `serverless architecture` in AWS that allows building and running the components of the 
platform without having to manage infrastructure.


### Why is it needed?
Imagine you are a product company whcih vision is to provide your clients with the best experience possible, the 
best way to know how to improve their experience is by making the right decisions at the right time. How can you
make sure you are not biasing your decisions on your perception only? Analyzing and interpreting data will give you
a competetive advantge. Of course you need to make sure data is available at the right time, with the right quality and 
with enough flexiblity to look at the whole universe around your product. 

By using 
This architecture breaks with the CAP therem which states that no system can handle enables to increase throughput, reduce latency and avoid silly 
data processing errors.

By using a serverless architecture, your developers can focus on their core product instead of worrying about managing and operating servers or runtimes, either in the cloud or on-premises. This reduced overhead lets developers reclaim time and energy that can be spent on developing great products which scale and that are reliable.
## What are the benefits of using lambda architecture?

## Model of a data platform using lambda architecture in AWS

## Samples of how can be useful
 
