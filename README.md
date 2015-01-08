* npm install -g express express-generator -> installs express and express-generator
* express blog --ejs -> creates template for blog (using ejs as templating engine)
* edit packages.json to include monk and mongo
* run mongod --dbpath ./data -> starts mongo daemon
* create database via mongo, type "use lth-blog"
* add lines to use database in app.js
* edit routes/index.js to supply the database data to the site
    * change index to supply database
    * add addpost route
    * add deletepost route
* edit index.ejs to display the blog
