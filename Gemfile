source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.6.3"

# Bundle edge Rails instead: gem "rails", github: "rails/rails"
gem "bcrypt", "~> 3.1.12"
gem "bootstrap-will_paginate", "~> 1.0.0"
gem "carrierwave", "~> 1.2.2"
gem "coffee-rails", "4.2.2"
gem "config"
gem "faker", "~> 1.7.3"
gem "figaro"
gem "jbuilder", "~> 2.7"
gem "jquery-rails", "4.3.1"
gem "mini_magick", "~> 4.9.4"
gem "pry"
gem "rails", "~> 6.0.0"
gem "uglifier", "3.2.0"
gem "will_paginate", "~> 3.1.6"
# Use Puma as the app server
gem "puma", "~> 3.11"
# Use SCSS for stylesheets
gem "sass-rails", "~> 5"
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem "webpacker", "~> 4.0"
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem "bootstrap-sass", "3.3.7"
gem "turbolinks", "~> 5"
# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.2", require: false

group :development, :test do
  # Call "byebug" anywhere in the code to stop execution and
  # get a debugger console
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  # Use mysql as the database for Active Record
  gem "mysql2", ">= 0.4.4"
  gem "rubocop", "~> 0.74.0", require: false
  gem "rubocop-rails", "~> 2.3.2", require: false
end

group :development do
  # Access an interactive console on exception pages
  # or by calling "console" anywhere in the code.
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "web-console", ">= 3.3.0"
  # Spring speeds up development by keeping your application running
  # in the background.
  # Read more: https://github.com/rails/spring
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  # Easy installation and use of web drivers to run system tests with browsers
  gem "webdrivers"

  gem "guard",                    "~> 2.13.0"
  gem "guard-minitest",           "~> 2.4.4"
  gem "minitest",                 "~> 5.10.3"
  gem "minitest-reporters",       "~> 1.1.14"
  gem "rails-controller-testing", "~> 1.0.2"
end

group :production do
  gem "fog", "1.42"
  gem "pg", "0.20.0"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
