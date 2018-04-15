<a id="footnote-1"></a>
# Markdown基本语法
---
## 多级标题
# H1
## H2
### H3
#### H4
##### H5
###### H6

## 字体特效
---
**强调**
_斜体_
_**强调的斜体**_ 
~~删除~~  
##超链接
---
[我是外链的超链接](http://www.baidu.com),
markdown对链接的语法为：`[]()`,如：`[我是外链的超链接](http://www.baidu.com)`  
试试页内的超链接：[我是页内的超链接](#footnote-1)，注：你先要在要跳转的到地方放置一个类似：`<a id="footnote-1">任意内容</a>`的锚点。由`id="footnote-1"`来匹配。

## 有序列表
---
1. 有序列表 1  
2. 有序列表 2  
3. 有序列表 3

## 无序列表
---
* 无序列表 1
* 无序列表 2 
* 无序列表 3

## 引用块
---
只需要在前面加 `>`,如下:

> 我是引用块


## 再看看代码块显示效果
---
markdown对代码块的语法是开始和结束行都要添加：\`\`\`,其中 \` 为windows键盘左上角那个，如下：

```

package fruitdiscernsystem;
public class Circle {
    private int x,y,r;
    public Circle(int x, int y, int r) {
        this.x = x;
        this.y = y;
        this.r = r;
    }
    public Circle() {
    }
    public int getX() {
        return x;
    }
    public int getY() {
        return y;
    }
    public int getR() {
        return r;
    }
    public void setX(int x) {
        this.x = x;
    }
    public void setY(int y) {
        this.y = y;
    }

    public void setR(int r) {
        this.r = r;
    }   
}

```


# 表格表示
---
| 靠左 | 居中 | 靠右 |
| :--- | :---: | ---: |
| 靠左 | 居中 | 靠右 |





