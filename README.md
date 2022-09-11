# Fullstack-App-Ruby-and-React

React frontend link: https://github.com/Katiechi/phase-3-project-frontend

Sinatra backend link: https://github.com/Katiechi/phase-3-sinatra-react-project


# About project
The project is a simple app that starts off with a login page, when you fill in your name,email and password, the details are captured in the backend to create a new authors data in the database.

You can then press the Go to write article button which will redirect you to another page that captures the title of the article/blog you want to write and the contents of the blog. Once you fill the title and contents section and press add, the data is captured and sent to the backend to be stored in the database under posts which is the second model after authors model. 

You can press the Go to articles button to view all the articles in the database and you can also delete the articles from the database.

For the backend, all the magic happens in the application controller.rb file. There the logic for getting all the data from the database,adding data and deleting data can be found.

# How to launch the project

For the frontend just fork the frontend github repo and npm start to start up the frontend.
For the backend also fork the backend github repo to your local machine and run "bundle exec rake server" on your terminal to startup the backend server
