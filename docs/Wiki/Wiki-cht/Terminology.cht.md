> 介紹 / 詞彙

*papoGen.css*中的一些專有名詞

---
## 1. Components的類別

*papoGen.css*把各個component分類成各種類別，用這四個特定的類別來定義專有的型別

| 型別 | 敘述 |
|---|---|
| *Globals* | *Globals*是一個可以應用於一個網站的通用樣式，包含CSS重置、網站通用字型、預設字體大小等等。注意*globals*包含網站通用主題包中的變數，可以被其他的component繼承或者調整 |
| *Layouts* | *Layouts*用來定義一個頁面的排版 |
| *Elements* | *Elements*是頁面中包含一個函式的元素，可以單獨存在，或者根據共同的標準，然後多個組織起來 |
| *Displays* | *Displays*用來表達特定的型別內容，該型別內容通常在頁面中會保持一致 |
| *Modules* | *Modules*是一種同時包含定義自身如何顯現以及自身如何運作的components，除此之外，*modules*通常會成群出現，並且包含各種不同的components |

---
## 2. 定義詞彙

以下的每個定義在本專案中是固定的，而且會常常用來敘述components

| 詞彙 | 敘述 |
|---|---|
| *Types* | *Types*是一種element的種類，通常可以調整元素的標準外觀，多個*Type*不能同時用在一樣的element上 |
| *Content* | *Content*只在componenet中的內文有意義，並且使用名稱來區分應該存在的content型別 |
| *Variations* | *Variations*調整一個element的各種數值(例如大小或者顏色)，*Variations*可以同時存在，以利於調整一個element |
| *States* | *States*表示一個element目前的修改狀態 |
