# 收集的一些简单的小游戏js版

#### 起因

​	之前就有练习过js写贪吃蛇之类的。	

​	2019.06.02学习js的面向对象时在[MDN](https://developer.mozilla.org/zh-CN/docs/Learn/JavaScript/Objects/Object_building_practice)中学习到了弹球小游戏，准备之后用js实现一些经典的小游戏。

#### 经过

##### 	2019.06.11

​	用js写了一个简单的贪吃蛇(代码02EatingSnake)([页面见此](https://blzbanme.github.io/funGamesOfJs/02EatingSnake/02EatingSnake.html))，没有参考别人的代码，可能存在一些bug = =。

​	当晚修改的bug：

​	1.蛇吃到自身会死亡，之前忘写这一块了。

​	2.按"上","下","左","右,改变蛇方向不是实时了（因为会存在和蛇移动时候访问蛇身体数组的临界区冲突，导致异常死亡）。

​	3.启动方式除了鼠标点击"start"，新增了按"任意键"。

​	4.增加判断，food不会产生在蛇身体中。