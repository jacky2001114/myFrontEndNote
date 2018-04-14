# HTML5 標籤

## HTML 標籤語義化

語議化是指把html的tag變得有意義起來，以住的網頁都是用div+css來編寫網頁，但是同一個tag會有不同的寫法，例如:

```markup
 <div class=navigator> , <div class=”toolbar”> , <div class=”nav”>,
     <div class="menu">...
```

這些tag都是代表同一件物件---導覽系統   
 因此為了統一化，HTML5新增了以下的語義化tag:

```markup
<article>    
<aside>    
<bdi>    
<details>
<dialog>    
<figcaption>
<figure>    
<footer>    
<header>    
<main>
<mark>    
<menuitem>
<meter>    
<nav>    
<progress>
<rp>
<rt>    
<ruby>
<section>    
<summary>
<time>    
<wbr>
```

以上tag的意思: [https://www.w3schools.com/html/html5\_new\_elements.asp](https://www.w3schools.com/html/html5_new_elements.asp)   
   
 這些語義化tag明確地把一個網頁的不同部分表示出來，其中有幾個最為常用:

```markup
<header>     主要用於定義內容的介紹展示區域
<nav>        定義導航鏈接的部分
<section>    定義文檔中的節（section、區段）。比如章節、頁眉、頁腳或文檔中的其他部分。
<article>    定義獨立的內容
<aside>      定義頁面主區域內容之外的內容（比如側邊欄）
<figcaption> 定義<figure> 元素的標題.
<figure>     規定獨立的流內容（圖像、圖表、照片、代碼等等）
<footer>     描述了文檔的底部區域
```

<<<<<<< HEAD:html/html5_tag.md
## 使用這些tag的好處:
1. 有利於SEO，有助於爬蟲抓取更多的有效信息，爬蟲是依賴於標籤來確定上下文和各個關鍵字的權重。
<br>
2. 方便其他設備解析（如屏幕閱讀器、盲人閱讀器、移動設備）以意義的方式來渲染網頁。
<br>
3. 於團隊開發和維護，語義化更具可讀性，而且遵循W3C標準的團隊都遵循這個標準，可以減少差異化。
<br>
4. 語義化的HTML在沒有CSS的情況下也能呈現較好的內容結構與代碼結構。

## 參考:

1. [HTML語義化](https://segmentfault.com/a/1190000005626375)
<br>
2. [ HTML5的新tag 語意化標籤](https://blog.chibc.net/learning/uibeginner-daily/859)
<br>
3. [理解HTML語義化](http://www.cnblogs.com/freeyiyi1993/p/3615179.html)
=======
參考用法: [http://www.runoob.com/html/html5-semantic-elements.html](http://www.runoob.com/html/html5-semantic-elements.html)

使用這些tag的好處:  
1. 有利於SEO，有助於爬蟲抓取更多的有效信息，爬蟲是依賴於標籤來確定上下文和各個關鍵字的權重 

2. 方便其他設備解析（如屏幕閱讀器、盲人閱讀器、移動設備）以意義的方式來渲染網頁 

3. 於團隊開發和維護，語義化更具可讀性，而且遵循W3C標準的團隊都遵循這個標準，可以減少差異化

 4. 語義化的HTML在沒有CSS的情況下也能呈現較好的內容結構與代碼結構

參考:

 1. [HTML語義化](https://segmentfault.com/a/1190000005626375)

 2. [HTML5的新tag 語意化標籤](https://blog.chibc.net/learning/uibeginner-daily/859) 

3. [理解HTML語義化](http://www.cnblogs.com/freeyiyi1993/p/3615179.html)

>>>>>>> 0d67f2f261fefcb58f1617574eeb5778512620de:html/html5-biao-qian.md
