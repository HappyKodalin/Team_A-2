# Team A-2 code

## Task1 模擬影片
[![Alt text](https://github.com/HappyKodalin/Team_A-2/blob/main/3363.png)](https://youtu.be/_5Xv-JR7kB4)

## Task2 模擬影片
[![Alt text](https://github.com/HappyKodalin/Team_A-2/blob/main/565.png)](https://youtu.be/YnPk6M07ZD0)

## Task3 GUI 與 IO按鈕 控制
### 1.利用GUI執行程式，也可更改手臂的移動速度。
(詳閱Task3 [GUI主程式](https://github.com/HappyKodalin/Team_A-2/blob/main/Task3%20GUI%20%E4%B8%BB%E7%A8%8B%E5%BC%8F)與按鈕程式)

👇GUI模擬測試影片

[![Alt text](https://github.com/HappyKodalin/Team_A-2/assets/55493510/5abdd5a8-316a-4539-b0d4-605c241f6c21)](https://youtu.be/j7sycMXbqHM)

👇GUI控制介紹
| 控制| 介紹 |
| ------------- | ------------- |
| 程式繼續  | 若手臂程式中途暫停按此按鈕可繼續動作。 |
| 程式暫停  | 暫停手臂程式。 |
| 程式結束  | 結束運作中的手臂程式。 |
| 回Home點  | 手臂回到Home點。 |
| 速度改變 | 跳出更改速度的介面。  |
| 主程式  | 執行main程式。  |
| Task1  | 執行Task1程式。  |
| Task2  | 執行Task2程式。  |
| 重製Tray盤燈號  | 重製LED燈號。  |
| LED燈號 | 偵測Tray盤目前的擺放狀況  |
  
![image](https://github.com/HappyKodalin/Team_A-2/assets/55493510/f1333059-2e8a-44d3-ada5-a1a21e031a00)

👇GUI速度變更介紹
| 控制| 介紹 |
| ------------- | ------------- |
| 速度(Speed)  | 輸入想要的速度。 |
| 加速度(Accel)  | 輸入想要的加速度。 |
| 確認  | 將輸入的速度與加速度，輸出至手臂程式，並關閉視窗。 |
| 取消  | 關閉視窗，程式速度不變。 | 
 
![image](https://github.com/HappyKodalin/Team_A-2/assets/55493510/036ceb34-b052-4d3b-ac7b-427098a8af55)

### 2.利用IO執行程式。

👇IO點位示意圖
![image](https://github.com/HappyKodalin/Team_A-2/assets/55493510/5771f457-9bdc-47ad-b43e-7c6453d77756)
👇IO點位用途介紹
| 按鈕顏色| 控制介紹 |
| ------------- | ------------- |
| 藍色按鈕  | Low power執行Task1程式。 |
| 白色按鈕  | Low power執行Task2程式。 |
| 紅色按鈕  | 結束手臂程式，並回到Home點。 |
| 橘色按鈕  | High power模式。 |
| 綠色按鈕  | 速度變更模式。 |
| 橘色+藍色按鈕  | High power執行Task1程式。 |
| 橘色+白色按鈕  | High power執行Task2程式。 |
| 綠色+藍色按鈕  | 增加手臂運行速度，每按一下藍色按鈕速度(speed)+10。 |
| 綠色+白色按鈕  | 降低手臂運行速度，每按一下白色按鈕速度(speed)-10。 |





