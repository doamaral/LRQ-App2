# README
This app follows the Khanrad Udemy course named "Learn Rails: Quickly Code, Style and Launch 4 Web Apps". This is the 2nd App. Just beginning
https://www.udemy.com/learn-rails/learn/v4/overview

# Few comments about the progress and troubleshooting:

* Bcrypt issue solved using the following line into the Gemfile gem 'bcrypt', git: 'https://github.com/codahale/bcrypt-ruby.git', :require => 'bcrypt'
* Styling with Bootstrap Template (https://bootswatch.com/simplex/): changed the assets/stylesheets/application.css file content for the Template generated
* Most part of the html content is in app/views/layouts/application.html.erb file
* Using Devise gem for authentication
* Using sqlite3 in Dev and Test, and postgresql in production in heroku https://blogmanerin.herokuapp.com/ (renaming app heroku: https://devcenter.heroku.com/articles/renaming-apps)
* Helpful article migrating from sqlite3 to postgresql https://medium.com/@helenflam/how-to-change-your-rails-app-database-from-sqlite-to-postgresql-before-deploying-to-heroku-ae2acc25c7ac
* I had a problem with Uglifier in Heroku deploy, commented this line in config/enviroments/production.rb -> # config.assets.js_compressor = :uglifier still figuring out why

# Comming soon:
* Social Sharing
