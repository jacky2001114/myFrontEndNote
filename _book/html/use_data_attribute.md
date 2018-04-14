# 使用data屬性

在製作網頁時，我們經常會加一些屬性讓自己更容易理解內容
但是每個人有不同的習慣，因此可能反而更加混亂。
<br>
有見及此，為了統一化，HTML5新增了一個名為<code>data-* Attributes</code>的屬性。能夠讓我們加入自定義的名稱和data。
## 用法
在使用<code>data-* Attributes</code>時，Attributes可以是任何字串，但不應該包含大寫英文字元和必定要有"data-"在前面。
<br>
<br>
基本語法:

```html
<element data-*="somevalue">


<ul>
  <li id="owl" data-type="bird">Owl</li>
  <li id="salmon" data-type="fish">Salmon</li>  
  <li id="tarantula" data-type="spider">Tarantula</li>  
</ul>

```
## 利用js來控制:
當有以下的tag加上showDetails(this)時，按下後便會alert出該element中的"data-type"後面的變數

### 方法1: getAttribute("attritube")
```js
function showDetails(animal) {
    var animalType = animal.getAttribute("data-type");
    alert(animalType);
}
```

### 方法2: dataset.attritube
```js
function showDetails(animal) {
    var animalType = animal.dataset.type;
    alert(animalType);
}
```
筆者不太推薦用方法2，因為此方法比較新，支援性低。
## 利用css來控制:
```css
#owl[data-type="bird"]{
    ...
}
#Salmon[data-type="fish"]{
    ...
}
#Tarantula[data-type="spider"]{
    ...
}
```

##  使用data屬性的好處:
  1. 増加可讀性，更容易維護。
  <br>
  2. 數據可以被js讀取，不需要透過ajax和database來獲得，今用戶有較好的使用體驗。


## 參考:
1. [w3schools](https://www.w3schools.com/tags/att_global_data.asp)
<br>
2. [[技術分享] 什麼是 HTML 5 中的資料屬性（data-* attribute)](https://pjchender.blogspot.hk/2017/01/html-5-data-attribute.html)
