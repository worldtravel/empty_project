source 'https://rubygems.org'

gem 'rails', '4.0.0'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

gem 'mongoid', git: 'git://github.com/mongoid/mongoid.git'
gem 'puma'
gem 'slim-rails'
gem 'bson_ext'

group :test do
  gem 'rspec-rails'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'guard-spork'
end

group :development, :test do
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'spork-rails', github: 'sporkrb/spork-rails'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# gem 'bcrypt-ruby', '~> 3.0.0'
# gem 'capistrano', group: :development
