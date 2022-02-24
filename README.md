# 藉由移動行為增加命中標的物的方法
ELECTRONIC DEVICE AND PREDICTION METHOD FOR SELECTING TARGET OBJECT

# 經濟部智慧財產局

- [專利連結](https://twpat3.tipo.gov.tw/twpatc/twpatkm?!!FRURLI708167)
- [專利公報下載](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/raw/main/document/GA-I708167.pdf)
- [公告說明書下載](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/raw/main/document/TB001556424_GN__1_108107178_I708167.pdf)

# 摘要
一種透過操作游標的行為來預測選取標的物之方法，可用於人機互動、虛擬與擴增實境、穿戴式技術，改善使用者操作體驗，其包含以下步驟：
藉由使用者操作游標取得不同因素，如距離、速度、方向等，得出對應數值。最後依照不同情境計算權重分數，用以預測標的物。使用者可更快的方式選取標的物，進而優化使用者操作體驗。

# 情境演示

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo01.gif)

本案提供更快的方式選取標的物，進而優化使用者操作體驗。

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo02.gif)


# 透過最短距離

- 設計概念

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo03.gif)

判斷所有目標距離是否大於距離閥值
![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/principle01.png)

# 透過坐標軸加權

- 設計概念

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo04.gif)

- 實際成果

此例 X坐標軸加權 乘以 0
![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo05.gif)

# 透過移動向量

- 設計概念

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo06.gif)


判斷游標移動速度是否大於速度閥值
![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/principle02.png)

- 實際成果

![](https://github.com/Jia-Hong-Peng/Jia-Hong-Peng-ELECTRONIC-DEVICE-AND-PREDICTION-METHOD-FOR-SELECTING-TARGET-OBJECT-NOTE/blob/main/image/demo07.gif)
