source 'https://rubygems.org'
#git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

#bootstrap
#gem 'bootstrap', '~> 4.0.0'
#gem 'jquery_ujs'
gem  'carrierwave'
gem 'bootstrap-sass', '~> 3.4.1'
gem 'jquery-ui-rails','~> 6.0.1'
gem 'bootstrap_form', '~> 4.2.0'
gem 'rails_bootstrap_navbar', '~>3.0.0'

gem 'bcrypt', '~> 3.1.7'

gem 'font-awesome-rails'

gem 'devise'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.3'


# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
 #See https://github.com/rails/execjs#readme for more supported runtimes

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
gem 'coffee-script-source', '1.8.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.2.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
 gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'yarn'
gem 'nokogiri'
gem 'rack', '~> 2.0.1'
gem 'rspec'
# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'rake', '~>12.3.3'

gem 'execjs', '~>2.7.0'

gem 'authlogic', '~>5.0.2'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  
  gem 'sqlite3'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do

  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

group :test, :production do
    gem 'pg'
      gem 'rails_12factor'
      
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
