source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5' # Was originally running '4.2.0' version on C9
# Use BCrypt gem for password hashing # Use ActiveModel has_secure_password
gem 'bcrypt',               '3.1.7'
# Use Faker to make sample users with semi-realistic names and email addresses
gem 'faker',                '1.4.2'
# Use image uploading (including resizing and production upload)
gem 'carrierwave',             '0.10.0'
gem 'mini_magick',             '3.8.0'
gem 'fog',                     '~> 1.36'
# Use pagination and appropriate bootstrapped pagination styles
gem 'will_paginate',           '3.0.7'
gem 'bootstrap-will_paginate', '0.0.10'
# Bootstrap gem: converts Less to Sass and makes all the necessary Bootstrap
# files available to the current application
gem 'bootstrap-sass',       '3.2.0.0'
# Use SCSS for stylesheets
gem 'sass-rails', '5.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '2.5.3'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '4.1.0'
# Use jquery as the JavaScript library
gem 'jquery-rails', '4.0.3'
# Turbolinks makes following links in your web application faster. Read more:
# https://github.com/rails/turbolinks
gem 'turbolinks', '2.3.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.2.3'
# HTML sanitization for Rails applications
gem 'rails-html-sanitizer',    '1.0.2'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '0.4.0', group: :doc
# Spring speeds up development by keeping your application running in the
# background. Read more: https://github.com/rails/spring
gem 'spring', '1.1.3'
# For React JS libraries inclusion/use in the front-end
gem 'react-rails', '~> 1.0'

group :development, :test do
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '1.3.9'
# Call 'byebug' anywhere in the code to stop execution and see debugger console
gem 'byebug', '3.4.0'
# Access an IRB console on exception pages or by using <%= console %> in views
gem 'web-console', '2.0.0.beta3'
end

group :test do
gem 'minitest-reporters', '1.0.5'
gem 'mini_backtrace', '0.1.3'
gem 'guard-minitest', '2.3.1'
end

group :production do
gem 'pg', '0.17.1'
gem 'rails_12factor', '0.0.2'
# Production grade web server for use with Heroku
gem 'puma',           '2.11.1'
end
