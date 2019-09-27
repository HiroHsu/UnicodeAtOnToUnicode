# UnicodeAtOnToUnicode
將原本是Unicode補完計畫中的外字字串轉換成Unicode編碼型式(&amp;#XXXX)

### 簡介
這個是多年前某傳產業專案中的小工具，用來轉換以前BIG5看不到日文，結果安裝中國海字集或者是Unicode補完計畫，導致無法與新軟體相容，產生方塊字，這個工具就是將外字字串轉換成Unicode編碼。

### 使用方式

首先Using

    uning uniEncoder

然後使用 Convert 方法進行轉換

    toUnicode.Convert(string)

