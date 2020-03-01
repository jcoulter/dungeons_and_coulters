# README

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



Dungeons and Coulters

sudo apt-get install gnupg2 -y

gpg --keyserver hkp://keys.gnupg.net:80 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

curl -sSL https://get.rvm.io | bash -s stable --ruby

rvm get stable --autolibs=enable
usermod -a -G rvm root

curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -


sudo apt install -y nodejs
sudo apt install gcc g++ make
sudo apt autoremove

gem update --system

echo "gem: --no-document" >> ~/.gemrc

 gem install rails -v 6.0.2.1
 
 gem install sqlite3
 
 gem install sassc -v '2.2.1' --source 'https://rubygems.org/'

https://www.howtoforge.com/tutorial/ubuntu-ruby-on-rails/
