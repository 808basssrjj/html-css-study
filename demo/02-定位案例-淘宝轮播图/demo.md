# 步骤

1. 大盒子我们类名为：  tb-promo      淘宝广告

2. 里面先放一张图片。

3. 左右两个按钮 用链接就好了。   左箭头 prev    右箭头  next   

   ​	左按钮样式（border-radius：左上，右上，右下，左下），

   ​	右按钮定位，提取左右按钮共同的样式代码（并集选择器）

4. 底侧小圆点ul 继续做。 类名为 promo-nav     

   ​	中间长方形椭圆 ul的定位（水平居中，离底部15px）  

   ​	长方形需要五个小圆点，ul无序列表，li浮动，椭圆中小圆点的样式



# 知识点：圆角矩形设置4个角

圆角矩形可以为4个角分别设置圆度， 但是是有顺序的

```
border-top-left-radius:20px;
border-top-right-radius:20px;
border-bottom-right-radius:20px;
border-bottom-left-radius:20px;
```

* 如果4个角，数值相同

  ~~~css
  border-radius: 15px;
  ~~~

* 里面数值不同，我们也可以按照简写的形式，具体格式如下:

~~~css
border-radius: 左上角 右上角  右下角  左下角;
~~~

还是遵循的顺时针。