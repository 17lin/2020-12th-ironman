# 隨機森林 (迴歸器)
[![Yes](https://img.youtube.com/vi/6sYMlwl2SWg/0.jpg)](https://www.youtube.com/watch?v=6sYMlwl2SWg)

## 今日學習目標
- 迴歸隨機森林
    - 了解隨機森林是如何處理連續性數值輸出
- 實作隨機森林迴歸器
    - 觀察隨機森林中的樹的數量是否影響預測

## 隨機森林中的隨機?
隨機森林中的隨機有兩種方面可以解釋:

1. 隨機取樣: 從訓練集中抽取n’筆資料出來，這n’筆資料是可以被重複抽取的。
2. 隨機特徵選取: n’筆資料隨機挑選k個特徵做樣本。

> 在 sklearn 中，最多隨機選取 𝑙𝑜𝑔𝑁 個特徵

![](https://i.imgur.com/6I6GmBN.png)



本系列教學簡報 PDF & Code 都可以從我的 [GitHub](https://github.com/andy6804tw/2020-12th-ironman) 取得！