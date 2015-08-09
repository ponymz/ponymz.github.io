---
layout: post
title: 代码高亮和评论功能测试
category: jekyll
---
代码高亮功能用了jekyll自带的Pygments，评论功能用的是友言，感觉都不怎么样，先用起来再说。

{% highlight java%}
public class MyArray {
	
	public static void main(String[] args) {
		
		String[] strArray = new String[1];
		Object[] objArray = strArray;
		
		//throws java.lang.ArrayStoreException
		objArray[0] = 1;
	}
	
}
{% endhighlight %}