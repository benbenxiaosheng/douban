# douban_spider
python框架的scrapy的入门学习项目，从豆瓣电影top250中，爬取相应信息存储在test.csv文件中
根据慕课网的"大壮老师"的"Python最火爬虫框架Scrapy入门与实践"课程，自己完成了课程里的代码部分

# 步骤
1. 从github链接 "https://github.com/benbenxiaosheng/douban_spider" 导入到pycharm
2. 安装scrapy，通过pip命令"pip install scrapy"进行安装
3. 运行：在pycharm的终端Termial输入命令"scrapy crawl douban_spider -o test.csv"

# 结果
在root目录(douban_spider文件夹里)出现了test.csv文件；用excel打开csv文件，显示抓取的信息内容
![Alt text](https://github.com/benbenxiaosheng/douban_spider/blob/master/QQ%E5%9B%BE%E7%89%8720200708221323.png)
