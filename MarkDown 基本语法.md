## MarkDown 基本语法

### 一、标题

typora中 使用ctrl+1/2/3 设置一/二/三 级标题

语法上为 n个#号后跟一个空格，如 （##+空格+文字=二级标题）



### 二、字体

- 加粗：ctrl+B  语法上为两个*包裹文字
- 斜体：ctrl+I   语法上为一个*包裹文字
- 斜体加粗  ctrl+B +ctrl+I  语法上为三个*包裹文字
- 删除线 Alt+Shift+5  语法上为两个~包裹文字



### 三、引用

Ctrl+Shift+Q， 语法上加n个>，可以嵌套。

> 引用
>
> > 引用
> >
> > > 引用



### 四、分割线

三个或以上的-/*+enter

---



### 五、图片

```bash
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```

<img src="C:\Users\Angela\Pictures\Saved Pictures\8ff1a2577ae023e8173e0e3d886cfb4.jpg" alt="实例" title="BTS" style="zoom:25%;" />

*markdown 图床



### 六、超链接

```csharp
[超链接名](超链接地址 "超链接title")
title可加可不加
```

[简书](http://jianshu.com)



### 七、列表

- 无序列表：-+空格
- 有序列表：数字+.+空格

1. 
2. 
3. 

- 列表嵌套：换行+tab 或换行+三个空格加-+空格



### 八、表格

```ruby
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
```

```ruby
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
```

| 姓名 | 技能 | 排行 |
| :--: | :--: | ---: |
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |



### 九、代码

 ctrl+shift+K

单行：语法上为用两个`包裹起来

多行：前后用三个`包裹

``` c++
code
```



### 十、流程图

注意：冒号后要加空格，否则会报错

~~~php
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```
~~~

```flow
st=>start: 开始
op=>operation: My operation
cond=>condition: yes or no
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```

