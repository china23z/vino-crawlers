# spider--zhihu
#####一：爬取知乎问题下的图片--女生拥有短发是怎样一中体验
    0：这一小段代码作用是，从知乎网上down图片，之前看到一个帖子--女生短发是一种什么样的体验？看到里面好多美女图片，就想着全部下载下来==
    1：登录的代码比较简单（大都大同小异），引用的是这位大牛写的author.py模块--https://github.com/wuchangfeng/zhihu-python--自己也在学习他的源码，down在工程里，索性直接引用了。十分欣赏。
    2：遇到网页需要加载更多时候，思路我看了http://lovenight.github.io这位大牛的，后来发现1中的代码也有这一部分的处理，我就自己对着浏览器的请求以及1中大神的代码，写出来了。
    3：之所以没有pull到1中大神project中,因为自己代码太渣。总之，会继续加上新的想法的。加油。
##### todolist
    0：把一中的代码优化成多线程，跑的太慢了，自己就爬了大概400多就关了它(而答案的数量有1560，一个答案至少一张图片吧)
    1：爬取知乎神评论，网上看到了关键的思想，好像有点数据挖掘的意思，会尽快弄出来
    2：爬取某一天知乎出现的评论最高的词或者其他的，用数据挖掘,分析的思想来处理
    3：爬取某个用户关注,回答，收藏等信息来分析该用户的行为特征.....
