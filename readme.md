项目名称：对部分环境数据的可视化及分析

作者：林澈

完成时间 2021 - 06 - 08

一共有两个版本：

app.R 是主要版本，作业绝大部分内容(几乎所有)在里面。

而app(无表格).R 中的数据框无法显示，但地图可以在当前页面中显示，比较美观

原因是 Echarts.js和adminLTE.js都会使用$来作为一个调用的接口， 在JS层面产生了冲突， 所以不能同时使用

对此问题REmap的作者Lchiffon也无法解决

对此讨论的链接为 https://github.com/Lchiffon/REmap/issues/29

数据集分为三个，分别置于国家级、省级、县级三个文件夹内

参考论文为 Contry-level_CO2.pdf

论文链接为 https://www.nature.com/articles/s41597-020-00736-3#Sec6

数据链接为 https://www.ceads.net.cn/


部分学习时写的代码与参考资料位于文件夹学习与资料中

myself.xlsx是个人信息的一些能力自评

ggan1文件夹里是一些可视化的动图模式，gganimate的图片我试了几次都没办法在shiny上面进行展示，只会显示在Rstudio上面，所以放弃了。。

报告.docx是对软件进行一个简单的操作介绍。

R.app 是主要软件

R.app 是主要软件

R.app 是主要软件
