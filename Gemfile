# frozen_string_literal: true

source "https://rubygems.org"

gem "rails", "5.2.3"
# Use sqlite3 as the database for Active Record
gem "sqlite3"
# Use Puma as the app server
gem "puma"
# Use SCSS for stylesheets
gem "sass-rails"
gem "bootstrap-sass"
gem "font-awesome-sass", "4.7.0" # 3/28/2019: LOCKED DOWN
# Use Uglifier as compressor for JavaScript assets
gem "uglifier"
# Use jquery as the JavaScript library
gem "jquery-rails"
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem "turbolinks"
# Use ActiveModel has_secure_password
gem "bcrypt"

# pagination gem
gem "will_paginate"
gem "will_paginate-bootstrap"

# Use slim instead of erb
gem "slim"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem "byebug"
  gem "capybara"
  gem "factory_bot_rails"
  gem "faker"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rails-controller-testing"
  gem "rb-readline"
  gem "rspec-rails", "4.0.0.beta2" # 4/26/2019: LOCKED DOWN
  gem "selenium-webdriver"
  gem "simplecov", require: false
end

group :development do
  gem "bullet"
  gem "listen"
  gem "rubocop-rails_config"
  gem "spring"
  gem "web-console"
end
