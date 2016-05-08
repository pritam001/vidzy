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

####Install [Node](Simply hit https://nodejs.org)

As part of installing Node, you’ll get NPM (Node Package Manager) on your machine. NPM in Node is similar to Ruby Gems in Ruby and NuGet in .NET. We use NPM (or any package managers) to download and install open-source reusable packages / modules in our applications.

####Install Express Generator

Express Generator is a Node module that we use to scaffold an application. To install Express Generator, open another Terminal on Mac or Command Prompt on Windows and run:

    npm install -g express-generator
    
The -g switch here instructs NPM to install this package at the global level so it’ll be accessible to all your applications.

    cd Vidzy
    npm install 
    npm install nodemon -g
    npm install monk --save 
