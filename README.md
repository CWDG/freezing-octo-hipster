[![Build Status](https://travis-ci.org/CWDG/freezing-octo-hipster.png)](https://travis-ci.org/CWDG/freezing-octo-hipster)
# Freezing Octo Hipster

This is the twitter clone for the [Collegiate  Web Developers Group](http://cwdg.github.io).
This is based off of [Michael Hartl's Rails Tutorial](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book).

##How to this project started

###Get the app
```shell
git clone git@github.com:CWDG/freezing-octo-hipster.git
cd freezing-octo-hipster
```

###Install the dependencies and migrate the database
```shell
bundle install --without production
rake db:migrate
```

###Run the app
```shell
rails server
```

It's now running at port 3000

If you have features you want to add, feel free to fork this and make a pull request!
