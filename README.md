### Cubor输入法
* 全拼
  > 我们采用了袖珍简化字里的基础词表，词的数量是我们能找的最全的词表，而且每个词都加有权重；
* 全拼+声调
  > 声调表是团队里的其他成员构成，反正提取也很麻烦（词的重复率比较高），当两者Merge时我们要考虑到多音字的情况；
* 双拼+双形
  > 双拼词表我们用Java写了一个全拼转双拼的程序，形成了一张新的双拼词表；  
  > 双形来源于小鹤音形的词表，同样也需要写程序提取；  
  > 其实字的形码不一定都是两位码，有的只有一位，有的只有两位，而还有的词既有两位也有一位的形码;
* 双拼+声调
  > 这一步其实就很简单了，上面的步骤已经给我们提供了所需要的表，剩下的就是Merge操作；
* 反查器
  > 简介：使用Java Swing制作图形界面，用于实现如小鹤编码查询的功能；    
  > 功能：1.键盘按键点击事件+鼠标按钮点击事件；  
  &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;2.文本输入框为空且点击查询/ENTER_KEY时，弹出JDialog，阻塞其它窗口，点击确定按钮结束Dialog;  
  &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;3.输入单字并点击查询/ENTER_KEY，在JList一行一行的显示查询的内容；  
## 特别感谢
   [沈青川](https://github.com/ShenQingchuan)
   
         
