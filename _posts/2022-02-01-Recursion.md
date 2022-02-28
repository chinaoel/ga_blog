---
layout: post
title:  "Recursion"
date:   2022-02-20 11:10:13 +0800
categories: jekyll update
---
## **遞迴Recurison**
 >電腦程式中，副程式直接或間接呼叫自己就稱為遞迴。


* Fabonacci 數列: C語言遞迴實作
{% highlight C %}
int Fab(int n){
    if (n == 0 || n == 1) return 1;
    else return Fab(n-1) + Fab(n-2)
}

int main(void){
    printf("%d",Fab(10));
}
{% endhighlight C %}

 