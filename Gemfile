source 'http://rubygems.org'

gem 'rails', '3.2.1'
gem "health-data-standards", :git => "http://github.com/projectcypress/health-data-standards.git", :branch => "develop" 
gem "mongoid"
gem "bson_ext"
gem "pry"
gem "capistrano"
gem 'heroku'
gem "nokogiri"
gem 'devise'
gem 'omniauth'


group :assets do
  gem 'sass-rails', "  ~> 3.2.3"
  gem 'coffee-rails', "~> 3.2.1"
  gem 'uglifier', ">= 1.0.3"
end

gem 'jquery-rails'

group :production do
  gem "therubyracer"
  gem 'thin'
end


group :test do
  gem 'turn', :require => false
  gem 'minitest'
  gem 'feedzirra'
end