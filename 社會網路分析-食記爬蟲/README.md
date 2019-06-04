# 社會網路分析-食記爬蟲
[食記網站](https://ifoodie.tw/city/%E5%8F%B0%E5%8C%97)

:point_right: 針對美食評價網站去做分析，觀察最新熱門美食店家趨勢，思考哪些因素可能影響店家熱門程度、網站排行，進而影響未來排名變化

### 類別：
* 台北週人氣排行
* 台北月人氣排行

### 標籤：
* 標題
* 餐廳名稱
* 評級
* 美食所在區域
* 產生日期
* 觀看人數
* 收藏人數
* 推薦人數
* 多少人來過
* 多少篇食記

### 進度：
* 五月份：
  * 選擇需要的標籤抓取後進行資料處理，將爬蟲結果存成csv檔
  * 抓取四月、五月份各週資料
  * 完成初步視覺化圖表(待更新)
* 六月份：
  * 完成整體、概況、細節的視覺化圖表
  * 探討結論與衍生的商業意涵
  * 思考待改進部分

### 下一步：(六月完成)
>針對目前的進度，接下來...
* 思考哪些**標籤**是會對於**熱門度排行**產生影響，比重如何？同時也是值得關注的？
* 排名當中店家所在地區**出現次數**與**排名**的相關性
* 針對**文章標題**進行斷字分析，標題取名的**誇大程度**是否影響到排名？
* 使用**Power BI**或**Python**內建方法，製作**視覺化圖表**，去**分析商業意涵**


### 商業意涵方向：
* 整體：
  * 整體各區域/各名次的評級、觀看收藏推薦次數
  * 各週各區域曾經出現的排名
* 概況：
  * 各月各名次的評級、觀看收藏推薦次數
* 細節：
  * 各區域餐廳名次排名

### 結論：
* 對排名影響較大：**觀看次數**、收藏次數、推薦次數
* 對排名影響較小：**評級**、多少人來過、多少篇食記
* “**觀看人數**”標籤比較會對熱門度排行產生影響
* 網站**排名**導致**觀看次數大幅變化**，對店家曝光率影響很大
* **對排名給予自訂的評分**，可以看出各區域的差別，熱門店家集中在**中山、大安、中正區**
* 熱門地區除了要在各週**出現次數多**，**排名也要夠前面**才比較有影響力

### 不足的地方：
>針對這次完成的作業，覺得說...
* 這次只抓取**區域標籤**而沒有抓**詳細地址**，無法以地圖的方式呈現每家餐廳在**地理位置的相關程度**
* 這次只抓取**單一時間點**去做分析，缺少每個店家從開店以來**歷史紀錄與營運狀況**，無法掌握各方面因素進行**預測後續發展**
* 要**如何定義**標題的**誇大文字**去做統計？以及詳細對**每篇文章內容**進行分析
* 思考**最熱門店家**可以藉由高人氣**進行什麼活動**，**增加來客數**與**營收**？

### Analysis & Visualization：

>資料分析與視覺化流程

![Analysis & Visualization-1](https://github.com/KuoYuHong/crawling-everything/blob/master/%E5%B7%A8%E9%87%8F%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90-Tibame%E7%B6%B2%E7%AB%99%E7%88%AC%E8%9F%B2/%E5%9C%96%E7%89%87/Analysis%20%26%20Visualization-1.png)

![Analysis & Visualization-2](https://github.com/KuoYuHong/crawling-everything/blob/master/%E5%B7%A8%E9%87%8F%E8%B3%87%E6%96%99%E5%88%86%E6%9E%90-Tibame%E7%B6%B2%E7%AB%99%E7%88%AC%E8%9F%B2/%E5%9C%96%E7%89%87/Analysis%20%26%20Visualization-2.png)

#### Flowchart Create by [Mermaid Live Editor](https://mermaidjs.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbQ2hyaXN0bWFzXSAtLT58R2V0IG1vbmV5fCBCKEdvIHNob3BwaW5nKVxuQiAtLT4gQ3tMZXQgbWUgdGhpbmt9XG5DIC0tPnxPbmV8IERbTGFwdG9wXVxuQyAtLT58VHdvfCBFW2lQaG9uZV1cbkMgLS0-fFRocmVlfCBGW2ZhOmZhLWNhciBDYXJdXG4iLCJtZXJtYWlkIjp7InRoZW1lIjoiZGVmYXVsdCJ9fQ) Website

