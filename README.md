# MushroomGame
## Introduction
本次專案是利用Java開發一個Mushroom小遊戲，遊戲中會有許多掉落物，分為以下幾項:
1. Red Mushroom
2. Blue Mushroom
3. Turtle

## 規則介紹
### 掉落物
- Red Mushroom: 如下圖，為一般障礙物，會隨著時間進行而變大。



- Blue Mushroom: 如下圖，收集滿5個Blue Mushroom即可使用技能。



- Turtle: 如下圖，當接觸到Turtle，遊戲立即結束。

<img src="./mushroom.png" width = "100" height = "100" />
<img src="./b_mushroom.png" width = "100" height = "100" />
<img src="./turtle.png" width = "100" height = "100" />


### 技能
收集滿5個藍色香菇即可使用技能，當收集完成時
- 按下A按鍵，即可觸發減少Red Mushroom的數量。
- 按下S按鍵，即可讓隨著遊戲進行而變大的Red Mushroom返回原本的大小。

### 快捷鍵
- 如下圖，按下R按鍵，即可查看目前挑戰著挑戰時間最長紀錄，並且遊戲將會暫停。

![image key](./img/record.png)

## Build Process
- 輸入執行指令:
  ``` bash
  $ javac Project_pro.java
  $ java Project_pro
  ```