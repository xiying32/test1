## Assignment 01 写爬虫获得豆瓣的电影评论

从一个初始网页开始， 获得足够多的豆瓣电影评论（数据可以定义为3万部电影）

必须要获得的数据:

<豆瓣电影的id， 电影名称， 时间， 评论， 星级> 

例如: 

+ <21345, 阿甘正传， 1994， “简直太棒了”, 5>
+ <21345, 阿甘正传， 1994， “五星好评！！！”, 5>
+ <21345, 阿甘正传， 1994， “五星好评！！！”, 5>
+ <21345, 阿甘正传， 1994， “五星好评！！！”, 5>
+ <12314, 西游外传， 2001， “真懒！！！”, 1>

## Requirement

+ bs4   # beautiful soup 
+ requests
+ jieba
+ pandas

## 提交

1. 每个人提交自己的源代码工程；
2. 每个人提交自己爬去的数据csv文件; 

## 提示

1. 使用DFS 广度优先 进行遍历
2. 使用bs4, requests 进行解析；
3. 自己设计策略不要让豆瓣封号 :P
4. 使用python自带的csv文件读写存储文件

## 最终提示(实在写不出来的时候再看)

[源代码参考链接](https://github.com/fortyMiles/get_douban_comments)
