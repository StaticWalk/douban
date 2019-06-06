课程的地址[https://www.imooc.com/video/17524]
Scrapy爬虫框架入门及实践

注意事项：
中间件定义完之后在settings文件中启用
爬虫文件名和爬虫名字不能相同（spiders目录中不能有项目同名文件）


1.在items中创建DoubanItem  定义PO
2.写douban_spider.py
基本信息
数据抓取 + XPath
下页回调
存入数据库 + setting配置 + pipelines初始化
3.中间件
正向代理 ip中间件
用户代理UserAgent

yield和return：yield可以在返回一组数据后再处理下一组数据，减少了内存的浪费
有返回数据的作用，不同在于yield在返回值后还可以继续运行接下来的代码，而return在返回后就不执行代码

