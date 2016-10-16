# hpu
hpu开源项目

不论你是写JavaScript，还是PHP，亦或是Python，开心就好，happy hacking！

## 这是什么？

这是一个爬虫示例（javaScript），主要抓取学校官网的新闻公告等内容
这里是hpu app 的分支，这里并不限制你的编码方式，最终代码将整合到主项目中，为理工人提供新鲜的资讯服务。

## 示例URL

教务公告-通知公告-列表页
-- URL：http://jwc.hpu.edu.cn/jwc/main.jsp?classid=6
教务公告-通知公告-文章页
-- URL：http://jwc.hpu.edu.cn/jwc/news.jsp?id=1128

后勤-通知公告-列表页
-- URL：http://repair.hpu.edu.cn/dsh/Pchome/GetNewsListbySub?RowCount=59&PageIndex=1&PageSize=17&LgType=1&PID=0101
后勤-通知公告-文章页
-- URL：http://repair.hpu.edu.cn/dsh/Pchome/newsInfoDesc/ba0e970e-cb54-4b15-beff-a68000ae7cd8

新闻网-综合新闻-列表页
http://news.hpu.edu.cn
新闻网 综合新闻-文章页
-- URL：http://news.hpu.edu.cn/news/contents/544/118105.html

## 测试开发
如果你使用JavaScript进行开发，请注意：你可能需要解决跨域请求问题
建议使用：corsproxy

`npm install -g corsproxy`

`corsproxy`

你需要了解一些node，npm等，当然你不必去理解他们。

示例中使用bmob后端云作为数据库，如果你对此感兴趣，请访问http://www.bmob.cn/
当然你可不用它，测试时注释掉代码就可以了。

## 加入我们

请git本仓库代码，作为参考，
你不必按照示例中的方法，我们相信你有你的想法！
你可以将错误或建议发表在issues中。

## 开源协议
MIT

