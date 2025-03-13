source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.3'

# Use Rails 6.x version
gem 'rails', '~> 7.0'



# MySQL as the database for Active Record
gem 'mysql2', '~> 0.5'

# Puma app server
gem 'puma', '~> 6.0'

# SCSS for stylesheets
gem 'sass-rails', '>= 6'

# JavaScript Transpiling
gem 'webpacker', '>= 4.0'

# JSON APIs
gem 'jbuilder', '~> 2.7'

# Bootsnap for caching
gem 'bootsnap', require: false

group :development, :test do
  # Debugger tool
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Web console for exception pages
  gem 'web-console', '>= 4.1.0'
  # File change listener for auto-reloading
  gem 'listen', '~> 3.3'
  # Spring for speeding up development
  gem 'spring'
end

group :test do
  # Capybara system testing
  gem 'capybara', '>= 3.26'
  # Selenium WebDriver for system tests
  gem 'selenium-webdriver', '>= 4.0.0.rc1'
end

# Windows compatibility (tzinfo-data)
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Solidus gems
gem 'solidus'
gem 'solidus_auth_devise'

gem "responders"
gem "solidus_support", ">= 0.12.0"
gem "view_component", "~> 3.0"
gem "tailwindcss-rails", "~> 3.0"

group :test do
  gem "capybara-screenshot", "~> 1.0"
  gem "database_cleaner", "~> 2.0"
end

group :development, :test do
  gem "rspec-rails"
  gem "rails-controller-testing", "~> 1.0.5"
  gem "rspec-activemodel-mocks", "~> 1.1.0"
  gem "factory_bot", ">= 4.8"
  gem "factory_bot_rails"
  gem "ffaker", "~> 2.13"
  gem "rubocop", "~> 1.0"
  gem "rubocop-performance", "~> 1.5"
  gem "rubocop-rails", "~> 2.3"
  gem "rubocop-rspec", "~> 2.0"
end

gem "solidus_paypal_commerce_platform", "~> 1.0"

gem "solidus_admin", ">= 0.2"
