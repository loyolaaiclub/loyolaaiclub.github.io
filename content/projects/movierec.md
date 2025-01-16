---
title: Movie Recommendations
description: Recommend similar movies a user would like based on their Letterboxd account
author: Eric Spencer
tags: [project, prediction]
showToc: false

date: 2024-12-12T23:49:28-05:00
# weight: 1
# aliases: ["/first"]
# author: ["Me", "You"] # multiple authors
TocOpen: false
draft: false
hidemeta: false
comments: false
# canonicalURL: "https://canonical.url/to/page"
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
  image: logo.jpg     # image path/url
  alt: Loyola AI Club (LAIC) Logo     # alt text
    # caption: "<text>" # display caption under cover
  relative: false   # when using page bundles set this to true
  hidden: true# only hide on current single page
editPost:
  URL: https://github.com/NicholasSynovic/laic-website-hugo/content
  Text: Suggest Changes     # edit text
  appendFilePath: true   # to append file path to Edit link
---

We created two models to predict movies a user would like based on data from their
Letterboxd account. 

The content-based model recommends similar movies to the currently displayed movie and
the other model sorts a list of similar movies to a Users' watched and rated Letterboxd
reviews with a dataset.

You can view a live website where the models are hosted here:
[MovieRecF24](https://movierec-f24-e040c420e2f6.herokuapp.com)
A Letterboxd account is necessary to login, but no authentication is required to confirm
you own the Letterboxd data.

You can view the source code here:
[GitHub](https://github.com/loyolaAI/MovieRec-F24)
