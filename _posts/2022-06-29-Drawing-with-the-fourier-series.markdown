---
layout: post
title:  "Drawing with the Fourier series"
date:   2022-06-25 09:20:48 +0700
url: _posts\2022-06-25-Drawing-with-the-fourier-series.markdown
img: /drunk cat.PNG
categories:
---
### Deriving the Fourier series: 
The Fourier series is the idea that any given function can be represented by a sum of sinusoids with varying amplitudes and frequencies. In particular,  sin and cosine. 

Firstly, let's examine the properties of cosine. A sine function has a period of $$ 2\pi $$ and is an even function. This means that when we create a sum of cosine functions the resulting function will retain these properties - namely, continue to be a periodic and an even function regardless of their amplitude or frequency. These sums can be represented as: 

 $$\displaystyle\sum_{n=1} ^{\infty} a_n \cos(n 2\pi/T x)$$

 Where $$n={1,2,3...}$$ and $$T$$ is the period
 

The same can be applied for sine functions, however,they will be odd instead: 

 $$\displaystyle\sum_{n=1} ^{\infty} b_n \sin(n 2\pi/T x)$$

 Therefore, any arbitrary function can be composed of these even and odd parts, without being even or odd itself. Therefore, the sum of these sinusoids will allow us to represent any periodic function: 

 $$ F(x)=\displaystyle\sum_{n=1} ^{\infty} a_n \cos(n 2\pi/T x)+\displaystyle\sum_{n=1} ^{\infty} a_n \sin(n 2\pi/T x)$$

 A constant should also be added to account for sinusoids with "zero" frequency. Let this variable be $$a_0$$: 

  $$ F(x)=a_0+\displaystyle\sum_{n=1} ^{\infty} a_n \cos(n 2\pi/T x)+\displaystyle\sum_{n=1} ^{\infty} b_n \sin(n 2\pi/T x)$$

 Finally, as we have a general equation for the representation of any function $$F(x)$$. We can now rewrite this equation in exponential form as it is in trignometric form currently. 



<!-- ### Finding the Coefficients: 

 First Lets begin by finding a way to come up with a general equation for $$a_0$$. We can see that the variable, $$a_0$$ is the vertical shift of the function. We also have to note that the average value of each individual sinusoid for complete periods is equal to the midline(the vertical shift). 

This is important because, we can make us of the fact that averages of sums are equal to the sums of averages. This means that since the average of $$sin(nx)$$ is equal to the vertical shift or since $$sin(nx)$$ does not have any vertical shift the average is 0, the average of  $$\displaystyle\sum_{n=1} ^{\infty} b_n \sin(nx)$$ is also 0. The same logic can be applied to cosine. 

Hence, $$a_0$$ can be calculated as the average of the periodic function we want to model with the Fourier series, $$F(x)$$, as it is the vertical shift. Therefore we can calculate $$a_0$$ using finding the mean of $$F(x)$$.   -->


