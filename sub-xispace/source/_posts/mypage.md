title: 'hexo new mypage, image files in the posts folder'
tags:
  - Markdown
categories:
  - news
author: cn27529
date: 2021-09-20 18:41:00

---

使用 asset_img 的方式，圖片在\_posts/mypage 資料中，如下
```
{% asset_img cat2021.jpg This is an example image %}
```

{% asset_img cat2021.jpg This is an example image %}

使用 Markdown 的方式，如下
```
![alt=mycat](cat2021.jpg 'title=mycat')
```
![alt=mycat](images/cat2021.jpg 'title=mycat')

