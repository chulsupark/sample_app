# Ruby on Rails Tutorial: sample application

This is the sample application for
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

-------------------
I had to

:production
$ sudo apt-get install libpq-dev
- gem 'pg' for heroku
- heroku w/ --stack cedar (see Gemfile for details)
-  Ubuntu, JS
# 3.1.0 problems on Ubuntu
	gem 'execjs'
	gem 'therubyracer'
#PCS_END

----

public/stylesheets|images|...
to assets/
	Heroku
		config.assets.compile = true
      in config/environments/production.rb

----
