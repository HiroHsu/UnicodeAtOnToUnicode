# UnicodeAtOnToUnicode
將原本是Unicode補完計畫中的外字字串轉換成Unicode編碼型式(&amp;#XXXX)

### 簡介
這個是多年前某傳產業專案中的小工具，用來轉換以前BIG5看不到日文，結果安裝中國海字集或者是Unicode補完計畫，導致無法與新軟體相容，產生方塊字，這個工具就是將外字字串轉換成Unicode編碼。

### 安裝方式
#### 1.整個程式碼複製過去
打開專案後，複製
#### 2.使用Nuget安裝
套件頁面
https://www.nuget.org/packages/UnicodeAtOnToUnicode/

##### 使用 PM 安裝
PM > Install-Package UnicodeAtOnToUnicode -Version 1.0.0

### 使用方式
#### 轉換成編碼型式 (&amp;#XXXX)
首先Using

    uning UnicodeAtOnToUnicode

然後使用 ConvertToUnicodeType 方法進行轉換

    ToUnicode.ConvertToUnicodeType(string)

#### 轉換成 Unicode
首先Using

    uning UnicodeAtOnToUnicode
    
然後使用 ConvertToUnicode 方法進行轉換

    ToUnicode.ConvertToUnicode(string)
