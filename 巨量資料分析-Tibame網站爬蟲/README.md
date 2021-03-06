# 巨量資料分析-Tibame網站爬蟲 (取自2019/4/1網頁資料)
[TibaMe線上課程網站](https://www.tibame.com/courselibrary)

:point_right: 針對線上課程網站去做分析，思考哪些因素可能影響到課程熱門程度、課程趨勢，進而影響未來課程的規畫

### 課程類別：
* 人工智慧
* 區塊鏈
* 數位商務
* 遊戲設計
* 科技管理
* 雲端技術
* 行動應用
* 物聯網

### 標籤：
* 課程名稱
* 課程價格
* 修課人數
* 課程總長度

### 商業意涵方向：
* 整體：
    * 所有**免費/付費**課程人數、總長度
* 概況：
    * **各類**課程人數、價格、總長度分布
* 細節：
    * **某一類**課程人數、價格、總長度分析

### 結論：
* 免費比付費課程**平均多了三倍人數**，但兩者的**最大值是付費較高**，有2200多人修課

* **行動應用與科技管理**是兩個最熱門類別，價位在1200~1400算是中等

* 遊戲設計**有超過75%的課不到40人修課**，是最冷門類別

* 區塊鏈有**超過八成是免費課**，少部分課價錢較低，可能剛推出這類別，**講師們還在試水溫**

* 人工智慧課程總長度是所有類當中最長，**平均將近15小時**，可能範圍較廣需要較多時間來學會

### 不足的地方：
>針對這次完成的作業，覺得說...
* 透過爬蟲有找出當下最熱門課程，後續對這些課程能夠進行什麼深度分析？
* 這次只抓取單一時間點去做分析，沒有過去歷史紀錄或是熱門課程開課狀況，無法掌握最有潛力的課程和進行預測後續發展

### Analysis & Visualization：

>資料分析與視覺化流程

![Analysis & Visualization-1](https://github.com/KuoYuHong/crawling-everything/blob/master/%E5%B7%A8%E9%87%8F%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90-Tibame%E7%B6%B2%E7%AB%99%E7%88%AC%E8%9F%B2/%E5%9C%96%E7%89%87/Analysis%20%26%20Visualization-1.png)

![Analysis & Visualization-2](https://github.com/KuoYuHong/crawling-everything/blob/master/%E5%B7%A8%E9%87%8F%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90-Tibame%E7%B6%B2%E7%AB%99%E7%88%AC%E8%9F%B2/%E5%9C%96%E7%89%87/Analysis%20%26%20Visualization-2.png)

#### Flowchart Create by [Mermaid Live Editor](https://mermaidjs.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbQ2hyaXN0bWFzXSAtLT58R2V0IG1vbmV5fCBCKEdvIHNob3BwaW5nKVxuQiAtLT4gQ3tMZXQgbWUgdGhpbmt9XG5DIC0tPnxPbmV8IERbTGFwdG9wXVxuQyAtLT58VHdvfCBFW2lQaG9uZV1cbkMgLS0-fFRocmVlfCBGW2ZhOmZhLWNhciBDYXJdXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9fQ) Website
