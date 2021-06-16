---
# hugo new --kind post /posts/new-posts.md
title: "标题写在这"
date: '{{ now.Format "Monday, January 2, 2006"}}'
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: yokinzzz
# author: ["Me", "You"] # multiple authors
showToc: false # 展示目录
TocOpen: false # 打开目录
draft: false # 是否为草稿
hidemeta: false # 是否展示元信息(作者等)
comments: false
description: "描述信息写在这"
canonicalURL: "post原始网址"
disableHLJS: true # 是否启用高亮JS脚本
disableShare: true # 是否禁止分享
hideSummary: true # 是否隐藏简介
searchHidden: false # 是否可以搜索
ShowReadingTime: true # 是否展示阅读时间
ShowBreadCrumbs: true # 是否展示文章路径
ShowPostNavLinks: true # 是否展示下一篇文章
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