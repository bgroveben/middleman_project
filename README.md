## README

This project is built using Middleman. I'm following the startup guide at https://middlemanapp.com.

I'm adding a config.ru file just in case I want to deploy what I have built to Heroku (or another Rack-based host).

When the static code is ready for delivery, run:
$ bundle exec middleman build

When the site is ready to deploy run:
1. $ middleman build [--clean]
2. $ middleman deploy [--build-before]
