# 现在是一级标题
>1. 关于以及标题的书写有很多 可以是当前的# 后面加空格+文本
>2. 也可以是用 文本换行 再加一个=下面就是第二种方法的演示

这里同时也是一级标题
=
那么这里就是第二级标题
-

> 上面的两个标题的写法 也只能到这里，也就是说，这种方法（=、-）只能用于两种标题

### 这里是三级标题
#### 这里是四级标题
###### 以此类推 这里是六级标题

## 还是回到二级标题
>下面来看一下一些普遍的字体
1. *斜体*
2. **粗体**
3. ***粗斜体***
4. 粗斜体也可以这样 ___粗斜体___
5. 这是删除文本 ~~删除文本~~

---
我习惯用上面那种方式来创建分割线  
当然也有下面这几种方法
***
* * *

## 创建有序列表和无序列表
>其实上面已经多多少少演示过了   
>无序列表就是 用+ 然后空格 或者* 然后空格  
>而有序列表就是1. 然后空格+文本

### 这是有序列表和无序列表和区块的综合 具体综合运用
#### 有序列表
1. >这一行是有序列表和区块的应用其实不应该这么写
>1. 这样写比较顺眼，也比较符合逻辑
>2. 让我们继续吧
>3. 是的就是这样下去

#### 无序列表 
>其实就是前面没有标号，如下
+ 这是无序列表的第一行
+ 这是无序列表的第二行
* 这样写也可以啊
* 是的这样写也可以

## **这是有序列表和无序列表的混用**
>无序列表作为有序列表的子列表的时候，需要再子列表的字段前面加一个Tab键
1. 考研
    - 英语
    - 数学
    + 政治
    * 专业课
2. 出国
    - 雅思
    + 托福
    * GRE
3. 工作
    - 代码
    + 面试
    * ....

## **代码的引用**
---
### **行内代码**
>行内代码用 `代码`标识，可嵌入文字中，下面举例子 
1. 我在`python`里面使用了`pygame`模块去写一个移动的矩形
2. how to use `scanf()` in  C
---
### 代码块
>代码块使用tab键或者三个点```标识
    
    这就是一个代码块
        import pygame
        import sys
        from pygame.locals import *

        pygame.init()...
    

```python
还可以指定是什么语言的代码块，也就是有语法高亮
import pygame
import sys
from pygame.locals import *

pygame.init()
screen = pygame.display.set_mode((600,600))

```
>第二种方法以三个点+语言开头，最后要以三个点结尾
----


## **下面是初学者觉得比较麻烦的表格**
>先说一下表格对其格式的几种语法  
>1. 居左  `:----`  
>2. 居中  `:----:` 或者`-----`
>3. 居右  `----;`
----
### **下面来创建表格吧**
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |


----
现在时间是2020/7/3那今天的markdown练习就先到这里吧

