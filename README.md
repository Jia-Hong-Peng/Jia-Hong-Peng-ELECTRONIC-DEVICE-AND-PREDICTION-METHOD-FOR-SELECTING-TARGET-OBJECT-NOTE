# 藉由移動行為增加命中標的物的方法
ELECTRONIC DEVICE AND PREDICTION METHOD FOR SELECTING TARGET OBJECT

# 經濟部智慧財產局

- [專利連結](https://twpat3.tipo.gov.tw/twpatc/twpatkm?!!FRURLI708167)
- [專利公報下載](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/raw/main/document/GA-I708167.pdf)
- [公告說明書下載](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/raw/main/document/TB001556424_GN__1_108107178_I708167.pdf)

# 摘要
一種透過操作游標的行為來預測選取標的物之方法，可用於人機互動、虛擬與擴增實境、穿戴式技術，改善使用者操作體驗，其包含以下步驟：
藉由使用者操作游標取得不同因素，如距離、速度、方向等，得出對應數值。最後依照不同情境計算權重分數，用以預測標的物。使用者可更快的方式選取標的物，進而優化使用者操作體驗。

# 專利範圍
一種透過操作游標的行為來預測選取標的物之方法，包含：

* a. 使用者操作游標；
* b. 計算游標與所有標的物的距離、速度、方向；
* c. 判若斷所有目標距離是否大於距離閥值；若小於距離閥值，則選取最短距離之標的物。  
  - 1) 使用者決定標的物是否命中；若命中，則結束。
  - 2) 若未命中，則判斷是否存在前一次標的物；若存在則清除標的物；到 a. 。

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/principle01.png)

* d. 若大於距離閥值，判斷是否存在前一次標的物，若不存在，則依情境使用不同方向的權重，計算所有標的物加權後的距離來選取最短加權距離之標的物；到 f.。
* e. 若存在前一次標的物，則判斷移動速度是否大於速度閥值；若大於速度閥值，則以前一次標的物為基準，再依移動方向選取距離最近標的物。  
  
![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/principle02.png)

* f. 使用者決定標的物是否命中；若命中，則結束。
* g. 若未命中，則保存當前之標的物；到 a. 。

# 情境演示

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo01.gif)

本案提供更快的方式選取標的物，進而優化使用者操作體驗。

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo02.gif)


# 透過最短距離

- 設計概念

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo03.gif)


# 透過坐標軸加權

- 設計概念

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo04.gif)

- 實際成果

此例 X坐標軸加權 乘以 0
![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo05.gif)

# 透過移動向量

- 設計概念

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo06.gif)


- 實際成果

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo07.gif)
