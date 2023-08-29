# Web-scraping


使用Python腳本示範各種網路爬蟲和數據處理任務，使用的庫包括`requests`和`BeautifulSoup`等。每個腳本專注於特定的任務或網站，以收集和處理數據。


## Podcast RSS Feed 爬蟲

此腳本從podcast的RSS供稿中提取特價優惠或連結，並使用`requests`、`BeautifulSoup`和`re`。主要功能包括：

- 使用`requests`獲取RSS內容。
- 使用`BeautifulSoup`提取集敘述。
- 使用正則表達式從集敘述中刪除HTML標籤。
- 使用模式匹配提取特價優惠或連結。
- 顯示結果。

#

## 在 Podcast RSS Feed 中搜索關鍵字

此腳本在podcast的RSS內容的標題和集敘述中搜索用戶輸入的關鍵字，使用`requests`和`BeautifulSoup`。主要功能包括：

- 使用庫`requests`獲取RSS內容。
- 在標題和集敘述中搜索關鍵字。
- 顯示相關集信息。

#

## 東森新聞文章爬蟲

此腳本使用`requests`和`BeautifulSoup`從特定網站爬取新聞文章。腳本的功能包括：

- 使用庫`requests`獲取網站的HTML內容。
- 使用`BeautifulSoup`解析HTML內容。
- 提取新聞文章的標題和發布日期。
- 顯示結果。

#

## 其他爬蟲內容
- 衛福部
- 松果購物
- PTT



