## 1-4 HTML基本語法

HTML的跟我們人一樣，有頭有身體，所有的HTML語法皆是由小於【&lt;】的符號當開頭，大於【&gt;】的符號當結尾，而基本語法如下，所有語法皆使用&lt;html&gt;標籤所包住，內部有&lt;head&gt;放置網頁屬性，不會顯示於瀏覽器中，多在此處設定網頁屬性或引用檔案，如：引用css、javascript等檔案，&lt;body&gt;標籤的內容則會顯示於瀏覽器中，而語法結束需以【&lt;/ &gt;】符號當作結尾，與開頭不同的地方是在【&lt;】後方加入除【/】的符號來當結尾。

```
<!DOCTYPE html>
<html lang="zh-Hant-TW">
    <head>
        <meta charset="UFT-8">
        <title>網頁標題</title>
    </head>
    <body>
        網頁內容
    </body>
</html>
```



