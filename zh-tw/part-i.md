# 第一部分：資料系統基礎

本書前四章介紹了資料系統底層的基礎概念，無論是在單臺機器上執行的單點資料系統，還是分佈在多臺機器上的分散式資料系統都適用。

1. [第一章](ch1.md) 將介紹本書使用的術語和方法。**可靠性，可伸縮性和可維護性** ，這些詞彙到底意味著什麼？如何實現這些目標？
2. [第二章](Courses/ddia/zh-tw/ch2.md) 將對幾種不同的 **資料模型和查詢語言** 進行比較。從程式設計師的角度看，這是資料庫之間最明顯的區別。不同的資料模型適用於不同的應用場景。
3. [第三章](ch3.md) 將深入 **儲存引擎** 內部，研究資料庫如何在磁碟上擺放資料。不同的儲存引擎針對不同的負載進行最佳化，選擇合適的儲存引擎對系統性能有巨大影響。
4. [第四章](ch4) 將對幾種不同的 **資料編碼** 進行比較。特別研究了這些格式在應用需求經常變化、模式需要隨時間演變的環境中表現如何。

第二部分將專門討論在 **分散式資料系統** 中特有的問題。


## 目錄


1. [可靠性、可伸縮性和可維護性](ch1.md)
2. [資料模型與查詢語言](Courses/ddia/zh-tw/ch2.md)
3. [儲存與檢索](ch3.md)
4. [編碼與演化](ch4.md)


------

| 上一章             | 目錄                            | 下一章                                       |
| ------------------ | ------------------------------- | -------------------------------------------- |
| [序言](preface.md) | [設計資料密集型應用](README.md) | [第一章：可靠性、可伸縮性和可維護性](ch1.md) |