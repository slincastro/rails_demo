# README


## PREREQUISITES
#### DATABASE
Use Postgresql

#### Ruby version Manager
RVM is sugested as ruby ​​version manager. This guide uses rvm.

Install from  https://rvm.io/rvm/install

Note: Rbenv is another option


## LOCAL ENVIRONMENT CONFIGURATION

Download the code from github repo

#### Install ruby and gems for the app

Copy the file `.ruby-gemset-example` to `.ruby-gemset`

In a OS console:

1. Go to app folder  
example:  
```cd my_workspace/rails_demo```
2. rvm shows if install a new ruby version is needed.
3. Install the bundler for manage the gem set for the app  
run: `gem install bundler`
4. Install the gem set  
run: `bundle install`  
This action will download from ruby gems repository and wrapper the gemset with the name inside of .gemset file

#### Setup db
The file `config/database.yml` has the configurations of database.
be sure to configure username and password for local and test base.

In a OS console run:  
`rake db:setup`  
in order to create the development and test databases


#### Run the server

In a OS console run:  
`rails server`  
Check the welcome page in a browser with:
`localhost:3000`


Pendiong Things you may want to cover:




* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
