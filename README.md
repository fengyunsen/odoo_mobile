# odoo_mobile 
## 图文演示 http://blog.sina.com.cn/s/blog_bc7dee2d0102xrl7.html
vux 实现对接odoo 配置出手机端 ()
![](https://github.com/gilbert-yuan/odoo_mobile/blob/10.0/mobile/odoo_mobile.gif)


图片示例
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/QQ20180629-101702.png)
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/QQ20180629-101646.png)
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/QQ20180629-101742.png)
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/2018-07-23%2017.23.37.gif)
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/2018-07-23%2017.27.12.gif)
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/2018-07-23%2017.27.47.gif)
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/2018-07-23%2017.31.17.gif)
![](https://github.com/gilbert-yuan/odoo_mobile/blob/8.0/mobile/description/2018-07-23%2017.30.40.gif)
1. 安装模块
  找到对应的版本安装模块
    
2. 配置手机端的要显示的模型 Grid Action View
   字段的设置还不完善。
   
3.访问链接登录 http://127.0.0.1:8888/odoo/mobile#/odoo/grid
  
测试性，写odoo 8 的手机端，功能尽量做到能配置页面。odoo模块对应的是8.0

待完善地方

1. 前端登录页面的创建
2. odoo模块 中write 方法的进一步的完善
3. 按钮的隐藏显示的完善，按钮的样式
4. 字段的显示的完善。
5.readonly form的美化
6.集成进去pyecharts 在手机端能够方便的查看 查看一些简单的报表视图

使用、开发odoo很长一段时间了，受odoo的影响，在做一些工功能的时候就会想着做成可以配置的。
所以就有了现在的模块，公司已经对接了微信，所以很多小功能就希望写在微信中，希望在微信里面有快捷的操作的页面。

这个是初始的需求，加班调休功能做到手机端。

:-: 过了几天居然又要求加一个报销功能，也要加到手机端。于是就在想能加到手机端当然是很棒的呀，很方便，但是写的时候却是很痛苦，每个页面都要手动的写太麻烦了，因为是erp类的给内部员工用的，页面也不需要很炫，特殊的定制化的东西也是比较少，可不可以像odoo一样可以在后台进行配置呢，然后前台就动态的显示页面于是就有了现在的项目


 

## pyechart 是一个极好的库希望能够进一步学习这个库 抽时间把它应用到这个项目中

