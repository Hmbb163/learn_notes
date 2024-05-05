# Hello word!

## ohou

<!-- 视图快捷键： CTRL+k ，v-->
### yeah!

#### ohhh

**加粗**

不加粗

*斜体*

不斜体

~~删除线~~

不删除线

* 今年
* 明年
* 去年
  * 什么？
    * 哦哦
      * 还行吧
        * 哈哈哈

---
1. 好吧
2. 是的
3. 还行
   1. 你好
      1. 我好
         1. 大家好！！！
   
> 你猜我在干嘛?
> emmmmmmmmm
    > sha sha sha 

---


```java
printf("hello world");
printf("你好这是行内代码！！！");
```


[超牛逼的超链接](https://zhuanlan.zhihu.com/p/366596107)

[图片名称](图片地址)

<!-- 什么？？？这是注释！别人看不见哦~~~ -->

|表格|表头|
|---|---|
|什么？|就杨吧|
|1|2|

----

![alt text](Clip_2024-05-04_20-25-33.png)

一级标题
===

二级标题
---

## ==高亮==


- [ ] 待完成事项

- [x] 已完成事项


<!-- 似乎暂时还用不了 -->
|表头|表头|
|----|----|
|内容|内容|
|>|内容|

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容 |
| ^    | 内容 |


## 行内公式: 

单位圆 $x^2+y^2=1$

$x^3+y^6=10$

## 公式块:

$$
\begin{cases}
x=\rho\cos\theta \\
y=\rho\sin\theta \\
z=\rho\tan\theta \\
% \\是换行的意思，中间不能有空格
\end{cases}
$$

## 上标 

$x^2 + y^{12} = 1$

## 下标 

$x_1 + y_{12} = 1$

## 较小的行内行分数 

$\frac{1}{2}$

## 展示型的分式 

$\displaystyle\frac{x+1}{x-1}$


## 开平方 

$\sqrt{2}$

## 开 $n$ 次方 

$\sqrt[n]{2}$

### 数学公式中的 空格和换行 都会在编译时 被忽略，想要实现「空格」的效果，需要用特别的命令。

紧贴 $a\!b$

没有空格 $ab$

小空格 $a\,b$

中等空格 $a\;b$

大空格 $a\ b$

quad 空格 $a\quad b$

两个 quad 空格 $a\qquad b$

### 累加+累乘

累加 $\sum_{k=1}^n\frac{1}{k}  \quad  \displaystyle\sum_{k=1}^n\frac{1}{k}$

累乘 $\prod_{k=1}^n\frac{1}{k}  \quad  \displaystyle\prod_{k=1}^n\frac{1}{k}$

积分 $\displaystyle \int_0^1x{\rm d}x  \quad  \iint_{D_{xy}}  \quad  \iiint_{\Omega_{xyz}}$


### 括号修饰

用 \left 和 \right 可以让括号适配内部大小

圆括号 $\displaystyle \left(\sum_{k=1}^{n}\frac{1}{k} \right)^2$

方括号 $\displaystyle \left[\sum_{k=1}^{n}\frac{1}{k} \right]^2$

花括号 $\displaystyle \left\{\sum_{k=1}^{n}\frac{1}{k} \right\}^2$

尖括号 $\displaystyle \left\langle\sum_{k=1}^{n}\frac{1}{k} \right\rangle^2$


### 多行对齐

居中:

$$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$$

左对齐:

$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$

### 公式编号与引用

$$
x+2 \tag{1.2}
$$

$$
\begin{equation}
x^n+y^n=z^n
\end{equation}
$$

由公式 $(1.2)$ 可得到结论


