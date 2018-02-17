# README
Essa aplicação de Blog segue o tutorial do curso do Udemy: Learn Rails: Quickly Code, Style and Launch 4 Web Apps
https://www.udemy.com/learn-rails/learn/v4/overview

Algumas coisas que tem nesse projeto:

* Problema com Bcrypt solucionado só adicionando a Gem no Gemfile
* Styling with Bootstrap Template (https://bootswatch.com/simplex/)
* Devise
* Social Share (comming soon)
* Using sqlite3 in Dev and Test, and postgresql in production in heroku https://blogmanerin.herokuapp.com/
* Helpful article migrating from sqlite3 to postgresql https://medium.com/@helenflam/how-to-change-your-rails-app-database-from-sqlite-to-postgresql-before-deploying-to-heroku-ae2acc25c7ac
* I had a problem with Uglifier in Heroku deploy, commented this line in config/enviroments/production.rb -> # config.assets.js_compressor = :uglifier still figuring out why
