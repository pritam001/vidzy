# vidzy
===========================
Video rental store application Vidzy based upon MEAN stack

    MongoDB: the database engine we use to store the data.
    Express.js: the server-side framework for building web applications, similar to ASP.NET MVC or Rails.
    Angular: the front-end framework for building web applications  
    Node.js: the Javascript runtime environment




## Local Development / Testing
---------------------------------------
####Install [Sublime Text](http://sublimetext.com)

####Install [Mongo](http://mongodb.org)

Open Command Prompt as an administrator:

	md \data\db
	cd “C:\Program Files\MongoDB\Server\3.0\bin” (or wherever you installed MongoDB)
	mongod

####Install [Node](https://nodejs.org)

As part of installing Node, you’ll get NPM (Node Package Manager) on your machine. NPM in Node is similar to Ruby Gems in Ruby and NuGet in .NET. We use NPM (or any package managers) to download and install open-source reusable packages / modules in our applications.

####Install Express Generator

Express Generator is a Node module that we use to scaffold an application. To install Express Generator, open another Terminal on Mac or Command Prompt on Windows and run:

    npm install -g express-generator
    
The -g switch here instructs NPM to install this package at the global level so it’ll be accessible to all your applications.

    * cd Vidzy
    * npm install 
    * npm install nodemon -g
    * npm install monk --save 
    
    
## Usage
---------------------------------------
From the Command Prompt or Terminal, run the following command inside the Vidzy folder:

    nodemon 

Nodemon will start your web server on port 3000. You may receive a pop-up warning you that Node is going to access incoming connections. Make sure to allow access.

Now, launch your browser and navigate to:

    http://localhost:3000

## Populating Database
---------------------------------------
How do we populate our MongoDB database with some documents? MongoDB has a shell that you can access using Terminal on Mac or Command Prompt on Windows. However, working with shell is not very user-friendly. So, to make our job easier, we’re going to use a free tool called RoboMongo. Head over to http://robomongo.org and download RoboMongo for your operating system.

1.Launch RoboMongo. You’ll see a dialog box for connecting to a MongoDB server.

2.Click the Create link on the top.

    Change the name of this connection from New Connection to localhost. 
    Note the address of the connection. It points to localhost:27017. 
    By default, MongoDB starts on port 27017.

3.If you click the Test button, you may get an error like “Authorization skipped by you”. Don’t worry about it. You’ll be able to connect to your local MongoDB regardless.  

4.Save the connection settings. Back in the Connect dialog box, connect to localhost.

5.From the View menu, tick Explorer if it’s not already ticked.

