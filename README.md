#Updates

I've added support for Weibo and Dribbble in social links part.

[Demo](http://imallen.com)

#Configuration

Just add following two value in your `_config.yml`

    weibo_user: a11en # Your weibo id (NOT DISPLAY NICKNAME)
    dribbble_user: allenhsu

##Install

Type the code below in terminal.

	$ git clone git@github.com:allenhsu/greyshade.git .themes/greyshade
	$ echo "\$greyshade: color;" >> sass/custom/_colors.scss //Substitue 'color' with your highlight color
	$ rake "install[greyshade]"
	$ rake generate

#Greyshade

[Greyshade](https://github.com/shashankmehta/greyshade) is a minimal, responsive theme for Octopress. From [Shashank Mehta](https://github.com/shashankmehta), based on [Slash](https://github.com/tommy351/Octopress-Theme-Slash)  

[Demo](http://shashankmehta.in/archive/2012/greyshade.html)
  
##License

MIT: [http://sm.mit-license.org](http://sm.mit-license.org/)
