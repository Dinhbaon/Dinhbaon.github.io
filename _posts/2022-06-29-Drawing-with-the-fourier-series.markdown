---
layout: post
title:  "Drawing with the Fourier series"
date:   2022-06-25 09:20:48 +0700
url: _posts\2022-06-25-Drawing-with-the-fourier-series.markdown
img: /drunk cat.PNG
categories:
---
The Fourier series is the idea that any given function can be represented by a sum of sinusoids with varying amplitudes and frequencies. In particular,  sin and cosine. 

Firstly, let's examine the properties of cosine. A sine function has a period of $$ 2\pi $$ and is an even function. This means that when we create a sum of cosine functions the resulting function will retain these properties - namely, continue to be a periodic and an even function regardless of their amplitude or frequency. These sums can be represented as: 

 $$\displaystyle\sum_{n=1} ^{\infty} a_n \cos(nx)$$
 

The same can be applied for sine functions, however,they will be odd instead: 

 $$\displaystyle\sum_{n=1} ^{\infty} b_n \sin(nx)$$

 Therefore, any arbitrary function can be composed of these even and odd parts, without being even or odd itself. Therefore, the sum of these sinusoids will allow us to represent any periodic function: 

 $$ F(x)=\displaystyle\sum_{n=1} ^{\infty} a_n \cos(nx)+\displaystyle\sum_{n=1} ^{\infty} a_n \sin(nx)$$

 A constant should also be added to account for sinusoids with "zero" frequency. Let this variable be $$a_0$$: 

  $$ F(x)=a_0+\displaystyle\sum_{n=1} ^{\infty} a_n \cos(nx)+\displaystyle\sum_{n=1} ^{\infty} b_n \sin(nx)$$

  Finally, as we have a general equation for the representation of any function $$F(x)$$. However, in order to actually get an equation for any given $$F(x)$$ we now need to find a way to compute $$a_0$$, $$a_n$$ and $$b_n$$ for all $$n$$. 

