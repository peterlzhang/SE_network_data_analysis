# Stack Exchange Network
## Understanding users and products using the Stack Exchange network
<img src="stackexchange_image.png">

## Introduction

The Stack Exchange (SE) network is a collection of Q&A websites where enthusiast and experts come together to share their knowledge. Currently the SE network is one of the top 50 online sites with approximately 838 million views per month [1]. The network encompasses a wide variety of subjects ranging from home improvement to computer programming. 

[1]: Statistics reported at https://stackexchange.com/about

## Objectives

The objectives of this work are to understand SE users and related products to create a more cohesive and stronger SE network. To this end we consider three questions:

1) What are some of the characteristics of users who provide accepted answers? <br>
2) Which users have untapped potential that could be used to improve the Stack Exchange network? How much improvement could these users provide?<br>
3) Based on SE posts, what topics are important in the present and in the future? Are there opportunities for new SE sites?

Currently this analysis is focused on the SE site superuser.com which focuses on computer related topics. Future work will be applied to the entire SE network.

## Key results

1) A significant number of answer providers on superuser.com are contributors to unexpected SE sites like English.stackexchange.com <br>
2) Using machine learning, I identify 25,374 SE accounts that are not members of superuser.com but could potentialy provide up to 58,479 answers. This represents a 23.45% increase in answered questions. <br>
3) We analyze different hardware and software tag combinations and discover that Mac OS has significantly fewer questions related to graphics cards when compared to Linux, Ubuntu, and Windows.

## Broader impact

Forums and Q&A websites like Stack Exchange are one of the best places to ask questions and resolve problems quickly. In this work, we are able to better understand the SE network as a whole when hidden connections are revealed. This promotes thinking of superuser.com as a part of the larger SE ecosystem. As SE sites can be created or closed, this information is relevant when considering whether to start or stop supporting an SE site. The same principles are relevant to other sites and can be extended a family of connected products, e.g. google, apple, windows, etc.

## Stack Exchange Data

The Stack Exchange network provides access to their website data at the [Stack Exchange Data Dump](https://archive.org/details/stackexchange). Currently there is over 60GBs of data available on users, posts, comments etc. Here we consider the user and post data from superuser.com and supplement the analysis with user data from the largest SE sites. 

- There are 1,038,245 superuser.com posts with 20 features such as title, tags, view count, and score.
- There are 803,552 users on superuser.com with 12 features such as reputation, upvotes, downvotes, etc.

In the final project, we will incorporate data from all SE sites.
