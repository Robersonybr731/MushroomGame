# MushroomGame
## Introduction
本次專案是利用Java開發一個Mushroom小遊戲，遊戲中會有許多掉落物，分為以下幾項:
1. Red Mushroom
2. Blue Mushroom
3. 烏龜殼

## 規則介紹
### 掉落物
- Red Mushroom: 如下圖左方，為一般障礙物，會隨著時間進行而變大。

- Blue Mushroom: 如下圖中間，收集滿5個Blue Mushroom即可使用技能。

- 烏龜殼: 如下圖右方，當接觸到烏龜殼，遊戲立即結束。

<div style="float:left;border:solid 1px 000;margin:2px;">
<img src="./mushroom.png" width = "100" height = "100" />
<img src="./b_mushroom.png" width = "100" height = "100" />
<img src="./turtle.png" width = "100" height = "100" />
</div>


### 技能
收集滿5個藍色香菇即可使用技能，當收集完成時
- 按下A按鍵，即可觸發減少Red Mushroom的數量。

<img src="./img/downnum1.gif" width = "75%" style="text-align:center"/>

- 按下S按鍵，即可讓隨著遊戲進行而變大的Red Mushroom返回原本的大小。

<img src="./img/downsize1.gif" width = "75%" style="text-align:center"/>

### 快捷鍵
- 如下圖，按下R按鍵，即可查看目前挑戰著挑戰時間最長紀錄，並且遊戲將會暫停。

<img src="./img/record.png" width = "75%" style="text-align:center"/>

### 遊戲結束
- 當碰到烏龜殼時，遊戲立即結束，並且會記錄ID及挑戰持續時間到資料庫。

<img src="./img/over.png" width = "75%" style="text-align:center"/>

## Build Process
- 輸入執行指令:
  ``` bash
  $ javac Project_pro.java
  $ java Project_pro
  ```