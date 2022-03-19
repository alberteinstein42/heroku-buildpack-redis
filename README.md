Heroku buildpack: redis
======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for adding redis to your application.

Testing
-------
heroku build -b .


Usage
----------


    $ heroku config:add BUILDPACK_URL=git://github.com/alberteinstein42/heroku-buildpack-redis.git

This will bundle redis into your instance without impacting your existing
system.
