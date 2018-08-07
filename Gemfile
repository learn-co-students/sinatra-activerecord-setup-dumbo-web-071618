# A sample Gemfile
source "https://rubygems.org"

gem 'sinatra'
# First, we'll add three gems to allow us to use ActiveRecord: activerecord
# version 4.2.5, sinatra-activerecord, and rake
gem 'activerecord', '4.2.5' # gives us access to the magical database mapping
# and association powers
gem 'sinatra-activerecord' # gives us access to some awesome Rake tasks
gem 'rake' # short for "ruby make", is a package that lets us quickly create
# files and folders, and automate tasks such as database creation
gem 'thin'
gem 'require_all'

# Into our development group, we'll add two other gems: sqlite3 and tux.
group :development do
	gem 'shotgun'
	gem 'pry'
	# will give us an interactive console that pre-loads our database and
	# ActiveRecord relationships for us
	gem 'tux'
	# our database adapter gem - it's what allows our Ruby application to
	# communicate with a SQL database
	gem 'sqlite3'
end

group :test do
  gem 'rspec'
  gem 'capybara'
  gem 'rack-test'
end
