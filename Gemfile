source 'https://rubygems.org'

ruby '2.2.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use mysql as the database for Active Record
gem 'mysql2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
group :development do
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'rubocop', require: false
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'annotate'
  gem 'dotenv-rails'
  gem 'dotenv-deployment'
end

group :development, :test do
  gem 'pry-rails'
  gem 'pry'
  gem 'pry-byebug'
  gem 'quiet_assets'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
#  gem 'spring'
#  gem 'spring-commands-rspec'
  gem 'faker'
  gem 'faker-japanese'
  gem 'database_rewinder'
end

group :test do
  gem 'simplecov'
  gem 'timecop'
end