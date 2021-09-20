title: post_asset_folder
author: cn27529
tags: []
categories:

- news
  date: 2021-09-20 18:14:00

---

開啟\_config.yml 設定

```
post_asset_folder: true
marked:
  prependRoot: true
  postAsset: true
```

使用 Markdown 嵌入圖像，在根目錄中加入 images 資料夾，然後放入圖片檔案

```
![alt=mycat](images/cat.jpg  "title=mycat")
```

![alt=mycat](images/cat2021.jpg 'title=mycat')

![alt=mycat](images/cat.jpg 'title=mycat')
