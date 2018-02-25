# crawler-twitter-hastag
介紹：
抓取特定的twitter hashtag 內文資料

爬蟲用法：
1.先上twitter 網頁，收尋需要的hastag 
![image](https://github.com/bEnWangg/crawler-twitter-hastag/blob/master/螢幕快照%202018-02-25%2015.23.37.png)


2.選擇"最新"
![image](https://github.com/bEnWangg/crawler-twitter-hastag/blob/master/螢幕快照%202018-02-25%2015.33.19.png)

3.複製網址
![image](https://github.com/bEnWangg/crawler-twitter-hastag/blob/master/螢幕快照%202018-02-25%2015.33.25.png)

4.將連結貼入twitter_crawler_selenium.ipynb中 In[2]的sourceurl 即可開始爬蟲

>爬蟲後會自動生成json檔，但其實是一般的文字檔而已
>資料在超過9000筆後可能會當掉
>關於selenium用法可參考
https://www.youtube.com/watch?v=49Mwqbu2cMo,大數據軟體有限公司
http://www.voidcn.com/article/p-gjyoltxq-bch.html


資料分析用法：
使用"讀取純文字檔.ipynb" 對爬取的資料做分析
>教學參考
https://marcobonzanini.com/2015/03/09/mining-twitter-data-with-python-part-2/





