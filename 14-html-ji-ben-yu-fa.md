# 1-4 HTML 基本語法

HTML 的跟我們人一樣，有頭有身體，所有的 HTML 語法皆是由小於【&lt;】的符號當開頭，大於【&gt;】的符號當結尾，而基本語法如下，所有語法皆使用 &lt;html&gt; 標籤所包住，內部有 &lt;head&gt; 放置網頁屬性，不會顯示於瀏覽器中，多在此處設定網頁屬性或引用檔案，如：引用 css、javascript 等檔案，&lt;body&gt; 標籤的內容則會顯示於瀏覽器中，而語法結束需以【&lt;/&gt;】符號當作結尾，與開頭不同的地方是在【&lt;】後方加入除【/】的符號來當結尾。

> HTML5 網頁範例

{% code-tabs %}
{% code-tabs-item title="HTML5 網頁範例" %}
```markup
<!DOCTYPE html>
<html lang="zh-Hant-TW">
    <head>
        <meta charset="UTF-8">
        <title>網頁標題</title>
    </head>
    <body>
        網頁內容
    </body>
</html>
```
{% endcode-tabs-item %}
{% endcode-tabs %}

> 語法說明：

{% code-tabs %}
{% code-tabs-item title="HTML5 網頁範例語法說明" %}
```markup
宣告此份文件為HTML5格式
由<html>標籤包住整份文件，並指定語言為臺灣使用的繁體中文
HTML的<head>中的內容不會顯示，可以在此設定一些屬性
設定此份文件編碼為UTF-8格式
設定此份文件標題為【網頁標題】
HTML<head>的結尾
將要顯示在網頁中的內容放置於HTML的<body>標籤內
在此放置要顯示出來的內容
HTML<body>的結尾
此處為HTML的結尾
```
{% endcode-tabs-item %}
{% endcode-tabs %}

