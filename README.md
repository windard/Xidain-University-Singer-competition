# Xidain-University-Singer-competition
西电校园歌手大赛
>这是我独立完成的第一个项目。自豪ing。。。

这是一个已经毕业的学长的的项目，刚开始我以为这是一个校园歌手大赛的PC版网页，
后来了解到它要通过微信的接口做一个移动端的网页，可能需要一些响应式布局，或者屏幕自适应的情况。
可是我才刚开始做网站前端的好么？那些那么高端的也仅仅只是略有耳闻，什么都不清楚啊。

然后先做PC端的试下吧，还行 其实整个网页并不复杂。
后来另一个学长看了源代码之后指出并不能在移动端上看。。
当然啊，我还不会嘛，就没有考虑过这个问题。

好吧，他教我加了一行代码，关于viewpoint，这是个让网页根据屏幕大小实现自适应的，还有chrome浏览器的开发者模式里面有一个可以模拟在手机页面里调试。
太棒了

那行代码是
    
'<meta content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=0" name="viewport">
'
    <meta content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,user-scalable=0" name="viewport">

加入了之后用chrome打开移动端调试，选择iPhone5，感觉很好的解决了网页在小屏幕无法看的问题。

over~
