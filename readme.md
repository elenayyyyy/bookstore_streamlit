`bookstore.py` 是使用 streamlit 製作的書店電商網站，大家可以以這個檔案為基礎修改成自己的網站。

這個網站主要分為 6 個頁面，分別為：

1. 登錄頁面
2. 商品總覽
3. 購物車
4. 結帳
5. 留言板
6. 購買歷史紀錄

我們目前的登錄帳號有兩個，分別為：

1. 帳號：``jsmith 密碼：`abc`
2. 帳號：`rbriggs` 密碼：`def`

若想新增帳號可以更新 `config.yaml`，我們將客戶的登錄資訊都寫在這個檔案中。

本組設定的購書情境為：購買10本以上書籍，即可享9折優惠

優化網站功能如下：
1. 完成合併購物車中相同書名的數量
2.新增團購按鈕
3.設定限時團購，從下單日起計算3天
4.若團購數量未達10本，則出現警告語，且無法以9折價錢購買書籍