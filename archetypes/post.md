---
# hugo new --kind post /posts/new-posts.md
title: "标题写在这"
date: '{{ now.Format "Monday, January 2, 2006"}}'
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: yokinzzz
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "描述信息写在这"
canonicalURL: "post原始网址"
disableHLJS: true # to disable highlightjs
disableShare: true
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "<image path/url>" # 文章封面
    alt: "<alt text>" # 图片若未加载，展示的文字
    caption: "<text>" # 图片描述
    relative: false # 当使用Hugo Bundle时，设为true
    hidden: true # only hide on current single page
    # weight: 1 如果需要置顶文章或者排序
editPost:
    URL: "https://github.com/<path_to_repo>/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---