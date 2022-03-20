# BookBorrowSystem
大學專案-圖書出借系統(Book-Borrow-System)

## 實作目的
在資料庫管理課程中，因為期末作品需要製作學習的成果，<br>
與組員討論後，決定要製作一個實際的借書系統，<br>
一方面是為了對SQL語言打好重要的基礎，<br>
而另外一方面則是可以加強自己對於實作專案的熟悉度。

## 設計理念與技術
主要使用C# WinForm的視窗程式來製作專案，<br>
根據驗證登入的不同，可分為使用者登入介面與管理者登入介面。
- Windows Form
- ADO.NET
- MSSQL
- MetroModernUI+CSkin


## 主要實作功能
實作功能包含完整的借書流程，並且實作出了書籍借閱排行榜與相對應的管理者介面，<br>
能夠進行詳細的CRUD等動作，也能夠依據書籍的欄位條件來進行書籍的查詢。
- 借書流程 (尋找書籍->檢查是否有人借閱->申請借閱->查詢借閱)
- 書籍借閱排行榜
- 後臺管理系統 (CRUD增刪改查操作)
- 使用者申報推薦書籍

## 相關程式畫面
### 登入註冊<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/7.png">
<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/8.png">
<br><br><br>

### 使用者<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/1.png">
<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/2.png">
<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/3.png">
<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/4.png">
<br><br><br>

### 管理者<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/5.png">
<br>
<img src="https://github.com/lfre84216/BookBorrowSystem/blob/main/6.png">
<br><br><br>


## 製作過程與困難點
在實作該專案的過程中，有嘗試想要實際讓資料庫可以被外部來連接，<br>
達成實際直接遠端資料庫的功能，<br>
所以在網路這方面有另外研究了關於虛擬伺服器的功能，<br>
讓實作出來的程式也能透過外部裝置來進行連線。
