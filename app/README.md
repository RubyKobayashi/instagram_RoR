# README

Instagram challenge using Ruby on Rails

**User Stories:**

* Any signed-up user can log in

```
As a user,
So I can use my account
I want to be able to log in
```

* Any signed-up user can log out

```
As a user,
So I can protect my account,
I want to be able to log out
```

* Any signed-up user can post photos

```
As a user,
So I can keep a collection of photos online,
I want to be able to upload photos
```
* Any signed-up user can connect with friends and family

```
As a user,
So I can be connected to my friends and family,
I want to be able to see their photos
```
* Any signed-up user can comment on a photo

```
As a user,
So I can make my presence known online
I would like to be able to comment on photos
```

* Any signed-up user can like a photo

```
As a user,
So I can show that I like a photo,
I want to be able to 'like' a photo
```


Things you may want to cover:

* Ruby version
  '2.6.0'

* System dependencies

* Configuration
  To run this project locally on your machine:

  1) Clone from this repo

  2) Install Homebrew by opening Terminal and running the following command:
  ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

  3) Install Ruby by opening Terminal and running the following command:
  brew install rbenv ruby-build
  # Add rbenv to bash so that it loads every time you open a terminal
  echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
  source ~/.bash_profile

  4)Install Ruby
  rbenv install 2.6.1
  rbenv global 2.6.1
  ruby -v

  5) Install Rails
  Installing Rails is as simple as running the following command in your Terminal:

  gem install rails -v 5.2.2
  Rails is now installed, but in order for us to use the rails executable, we need to tell rbenv to see it:

  rbenv rehash
  And now we can verify Rails is installed:

  rails -v
  # Rails 5.2.2

  5) In terminal while in project folder, run command:
    bundle


* Database creation

  Open terminal and run this command:
  brew install postgresql

* Database initialization
  Once this command is finished, it gives you a couple commands to run. Follow the instructions and run them:

  # To have launchd start postgresql at login:
  brew services start postgresql
  By default the postgresql user is your current OS X username with no password. For example, my OS X user is named chris so I can login to postgresql with that username.

* How to run the test suite
  In teminal run command:
  rspec

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
