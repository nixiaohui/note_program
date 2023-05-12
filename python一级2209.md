# 选择题

### 4.关于turtle的运动体系中，说法正确的是？（  ）

A. turtle.goto(x,y)可以让小海龟直线前进到指定的坐标位置。

B. turtle.forward(a)可以让小海龟向前移动a个像素，如果a为负数，运动方向不变，只是小海龟自身的方向与原来相反。

C. turtle.seth()、turtle.left()、turtle.right()的参数均为绝对角度。

D. turtle.dot()与turtle.circle()的参数均为半径。

### 5.在turtle画图中，常常使用turtle.color(color1,color2)指令进行画笔颜色和填充颜色的设置，下列关于该指令使用正确的是？（  ）

A. turtle.color(“red”,”yellow”)表示画笔颜色为黄色，背景颜色为红色。

B. turtle.color(“red”)表示画笔颜色为红色，背景颜色随机。

C. turtle.color(color1,color2)指令中的参数color2是可选项，可以只有一个颜色参数。

D. turtle.color(color1,color2)指令中若将color1和color2删掉，即turtle.color(),小海龟在向前走100像素时，画布不会出现小海龟的轨迹。

### 6.如图所示，想要将一行输出的两句诗词，变成二行输出方式，应该如何写输出指令？（ ）

A. print("床前明月光，疑是地上霜")

B. print("""床前明月光 疑是地上霜""")

C.

print("床前明月光

疑是地上霜")

D.

print("""床前明月光

疑是地上霜""")

### 7.绘制一个半径为5的红色圆点，下列选项不正确的是？（ ）

A.

```python
import turtle
turtle.color("red")
turtle.dot(10)
turtle.done()
```

B.

```python
import turtle
turtle.color("red","red")
turtle.begin_fill()
turtle.circle(5)
turtle.end_fill()
turtle.done()
```

C.

```python
import turtle
turtle.color("red","red")
turtle.begin_fill()
turtle.circle(5)
turtle.end_fill()
turtle.done()
```

D.

```python
import turtle
turtle.color("red","red")
turtle.begin_fill()
turtle.circle(5)
turtle.end_fill()
turtle.done()
```

### 8.下列指令可以方便将画笔设置回到初始位置和初始方向的是？（  ）

A. turtle.home()

B. turtle.clear()

C. turtle.goto()

D. turtle.setup()



### 9.如图所示，turtle.circle(100)是绘制一个半径为100的圆，请问画笔从以下哪个点出发开始绘制？（ ）

![image-20230512232448822](C:\Users\Administrator\Desktop\assets\image-20230512232448822.png)

A. A

B. B

C. C

D. D

### 10.Python自带的集成开发环境是？（  ）

A. iPython

B. Dev-C++

C. Visual Studio Code

D. IDLE

### 11.下面哪条语句不能输出：原创精神：自主可控！自主可控！自主可控！（  ）

A. print('原创精神：自主可控！自主可控！自主可控！')

B. print('原创精神：'+'自主可控！'*3)

C. print('原创精神：自主可控！'*3)

D. print('原创精神：'+'自主可控！’*2+'自主可控！')

### 12.在 IDLE 开发环境中，默认是以多少个空格作为代码的基本缩进单位？（ ）

A. 1

B. 2

C. 3

D. 4

### 13.turtle绘图中，设置画布高度500像素，宽度500像素，初始位置为（0,0）的代码是？（ ） 

A. turtle.screensize(500,500,0,0)

B. turtle.screensize(0,0,500,500)

C. turtle.setup(0,0,500,500)

D. turtle.setup(500,500,0,0)

### 16.下列运算符中，优先级最高的是？（ ） 

A. !

B. and

C. *=

D. *

### 18.关于下面程序，描述正确的是？（  ）

```python
import turtle
turtle.goto(100,100)
turtle.goto(100,-100)
turtle.goto(-100,-100)
turtle.goto(-100,100)
```

A. 运行代码后，会画出一个正方形。

B. 运行代码后，会画出一个正方形以及一条从(0, 0)到(100, 100)的连线。

C. 运行代码后，turtle面朝方向是水平向右。

D. 运行代码后，turtle面朝方向是竖直向上。

### 20.下列关于python语言说法正确的是？（ ） 

A. Python采用代码缩进和冒号':'区分代码之间的层次。

B. 在IDLE编写代码时，使用中文输入代码中的小括号或者双引号，任何位置都不会产生语法错误。

C. Python32位和64位的安装包没有区别，可以任意使用一个。

D. Pycharm和Microsoft Visual Studio都可以用来编写Python程序，但是语法和IDLE不一致。

### 22.下列程序的输出结果是？（  ））

```python
a=4
b=3
c=2
print(a*b**c)
```

A. 24

B. 144

C. 36

D. 12

### 24.print(20 or 15<20)的输出结果为？（ ）（2分）

A. True

B. False

C. 20

D. 15



# 编程题

### 36.每个人都知道自己的鞋码，但是不知道自己的脚长，请写一个程序，帮助大家利用鞋码算出脚长。

#### 要求：

1.允许用户输入自己的鞋码，并有提示语'请输入你的鞋码：'，不需要包括单引号；

2.计算鞋码，脚长 = (鞋码 + 10) / 2；

3.输出脚长，并有提示语'你的脚长是(单位:厘米）：'，不需要包括单引号。

#### 示例：

输入：38

输出：你的脚长是(单位:厘米）：24.0





### 37.按照要求绘制一个五角星：

(1)海龟初始位置的坐标为(0,0)；

(2)设置画笔大小为5,

(3)画笔颜色为红色(red)；

(4)五角星填充颜色为黄色(yellow)。

(5)五角星大小不限，但是要能清晰看出是五角星，并且完全在考试平台上显示出来。

提示：五角星每个角为36度。







___



36 参考程序：

n = input("请输入你的鞋码：")

n = int(n)

x = (n + 10)/2

print("你的脚长是（单位：厘米）：", x)

评分标准：

（1）有输入语句；（3分）

（2）有输出语句；（1分）

（3）有类型转化语句，并且类型转换正确，否则该项分数为0；（2分）

（4）有计算语句，并且计算正确，如果计算错误该项分数为0；（2分）

（5）程序符合题目要求，运行正确。（2分）



37 参考程序：

import turtle

turtle.pensize(5)

turtle.pencolor("red")

turtle.fillcolor("yellow")

turtle.begin_fill()

turtle.forward(200)

turtle.right(144)

turtle.forward(200)

turtle.right(144)

turtle.forward(200)

turtle.right(144)

turtle.forward(200)

turtle.right(144)

turtle.forward(200)

turtle.end_fill()

评分标准：

（1）海龟初始位置的坐标为(0,0);    (2分)

（2）有绘制线条;     (2分)

（3）画笔颜色设定为红色(red);       (2分)

（4）画笔大小为5;   (3分)

（5）五角星填充颜色为黄色(yellow);      (3分)

（6）能写出turtle.left(144)或者turtle.right(144);    (2分)

（7）能完全显示在考试平台（2分）

（8）画出完整的五角星。   (4分)





# 编程题

### 题目1

小海龟最近正在学习中国传统文化，小海龟对传统节日元宵节特别感兴趣，元宵节作为中国传统节日又被称为灯节，小海龟为了庆祝元宵节，它想绘制一个彩色的荷花灯图形，如下图所示：

![img](C:\Users\Administrator\Desktop\assets\9503_sbw5_7441.png)

要求：

（1）彩色荷花灯由5个花瓣组成，画笔颜色为粉色（pink）；

（2）相邻花瓣的对称轴夹角的角度为30度（提醒同学们程序中的旋转角度可不一定是30度）；

（3）单个花瓣的弧度为90度，半径为70；

（4）最左侧花瓣的上下两个线条中，上线条是小海龟左转105度后利用画圆工具绘制而成的；

（5）最后小海龟隐藏。



### 题目2

小明同学积攒了一部分压岁钱想要用来购买书籍，已知一本书的单价是23元，请根据小明压岁钱的金额，编写程序计算最多可以购买多少本书，还剩多少压岁钱。

要求：

（1）程序开始运行后，提示输入压岁钱数；

（2）程序会根据输入的数字计算最多可以购买多少本书并计算剩余的压岁钱金额；

（3）输出结果：可以购买XX本书，剩余XX元。

如：输入压岁钱100，输出：可以购买4本书，剩余8元。