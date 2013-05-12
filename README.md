#中文

##更新内容

增加了新浪微博和 Dribbble 连接的支持

[演示](http://imallen.com)

##设置方法

编辑你的 `_config.yml`，加入以下两行

    weibo_user: a11en # 注：新浪微博自定义网址中用户名部分或数字 ID，不是昵称
    dribbble_user: allenhsu

##安装方法

在命令行中使用以下命令安装：

	$ git clone git@github.com:allenhsu/greyshade.git .themes/greyshade
	$ echo "\$greyshade: color;" >> sass/custom/_colors.scss //Substitue 'color' with your highlight color
	$ rake "install[greyshade]"
	$ rake generate

#English

##Updates

I've added support for Weibo and Dribbble in social links part.

[Demo](http://imallen.com)

##Configuration

Just add following two value in your `_config.yml`

    weibo_user: a11en # Your weibo id (NOT DISPLAY NICKNAME)
    dribbble_user: allenhsu

##Install

Type the code below in terminal.

	$ git clone git@github.com:allenhsu/greyshade.git .themes/greyshade
	$ echo "\$greyshade: color;" >> sass/custom/_colors.scss //Substitue 'color' with your highlight color
	$ rake "install[greyshade]"
	$ rake generate

##Greyshade

[Greyshade](https://github.com/shashankmehta/greyshade) is a minimal, responsive theme for Octopress. From [Shashank Mehta](https://github.com/shashankmehta), based on [Slash](https://github.com/tommy351/Octopress-Theme-Slash)  

[Demo](http://shashankmehta.in/archive/2012/greyshade.html)
  
##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)
