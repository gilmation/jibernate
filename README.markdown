Jibernate/Hibernate module for DataMapper
=========================================

Some info
---------

There will be info

Howtos
---------

need to install maven3 (just grab it from http://www.maven.apache.org/download.html and change executable's name to mvn3)

setup the gems

    mvn3 gem:initialize

run the eventlog - list

    mvn3 ruby:jruby -Djruby.args="eventlog.rb list"

run the eventlog - store

    mvn3 ruby:jruby -Djruby.args="eventlog.rb store something"

rake tasks (please note the jruby.rake.args part(var name))

    mvn3 ruby:rake -Dverbose=true -Djruby.rake.args="--trace -T"

maybe you need to replace ther respective line in jibernate.script with

    SET WRITE_DELAY 0 MILLIS