== README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.


TechStack:
1. [React.js](https://facebook.github.io/react/)
2. [Ruby on Rails](http://rubyonrails.org/)


*How to run locally*
1. Install Postgresql
2. do `bundle install` on your home dir
3. go to `psql` and then run `create role hello with createdb login password 'world';`
4. rake db:create db:migrate
5. run `rails s` then go to `localhost:3000`
