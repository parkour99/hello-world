# Markdown 常用语法编写Readme 小计。

# 部分内容参考网址：[博文](http://blog.csdn.net/kaitiren/article/details/38513715)
详细的这位博主的markdown demo 参考github地址：[这里](https://github.com/guodongxiaren/README/blob/master/README.md)

## 标题级别如下六个

# hello
## hello
### hello
#### hello
##### hello
###### hello 

上面总共就6个级别的标题。

## 横线和虚线表示法

下面一个等号，上面不写文字，那么就有可以画一条直线。</br>
如果是三个以上减号，星号，下划线等，符号上面没有文字的话，就是一条虚线。

===

---

## 回车换行表示法

可以直接用html里的\<br>,这里用了反斜杠转义了，不转义就换行了。换行开始，<br> 换行结束。

## Tab实现单行文本。

    Hello。这句话前面有两个TAB，实现单行文本。
    
## 换行另一种办法：

这句话结尾有两个空格或者两个TAB，可以换行.  

## 高亮某一个关键字或内容

i am 用反引号高亮的`TAB`。

## 强调

表示**强调**，就要在要强调的词语前后各自输入两个星号，强调效果如下：**我是强调**.

## 无序列表表示及层级表示 

* hello
- world
  - world 这前面有个tab。层次越深，tab越多。
    层次级别，就用TAB。
  - 

## 有序数字列表

使用`1.`开头，后面都用`*`加上空格开头就自然顺序列表下去了。

1. hello
* hello

## 块缩进用`>`

> i am first hello
world 
>> i am second hello 
>>> i am third hello


## 插入链接 

[谷粉搜索](http://www.gfsoso.com)

## 插入图片

![baidu](http://www.baidu.com/img/bdlogo.gif)

## 给图片加入链接

[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo" 

## 代码片段

```python
imort os
print os.getcwd()
```
```java
import java.io.*
```
```c++
#include<iostream>
using namespace std;
int main(){ return 0;}
```


