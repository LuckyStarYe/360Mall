# 360Mall
Personal demo for practicing
1) 仿360商城写的demo，完成度较高。欢迎大神路过抛砖！
2）实现页面：首页、商品列表、商品详情、购物车、结算页面、注册、登录；
3）整体构架：对于页面中相同的部分，单独写成一个html文件（仅包括样式css、html、script，去掉头部尾部等多余的部分，然后通过ajax加载进来；
  PS：关于ajax 像Hbuilder、Webstorm等自带ajax运行环境，也可以自己下载个软件搭建本地服务器；
4）页面传值：采用cookie方式实现不同页面间数据的传递。一个cookie存所有注册账号、一个cookie存当前登录账号、并根据当前登录账号拼接购物车cookie
   这样就可以实现不同账号同时访问而不产生冲突了。
   PS：对于没有登录的情况统一设置一个名字为mycartadmin的cookie进行存储。这里有个梗就是多人同时登录的问题。解决一点击购物车的时候必须登录，显然这个不太合理；
   解决二此时再根据ip地址和登录时间去判断下；
   还有个cookie用来弥补解决商品详情间的情况。
5）主要功能及技术点：购物车页面的增删改查、商品详情页的分页效果、登录注册逻辑的实现、二级菜单、吸顶、首页的楼梯效果、ajax、跨域、轮播图、选项卡、代码封装等。