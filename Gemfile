# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# For use with client side single page apps such as the venerable. Read more: https://github.com/lynndylanhurley/devise_token_auth
gem 'devise_token_auth', '~> 1.2'
# Middleware that will make Rack-based apps CORS compatible. Read more: https://github.com/cyu/rack-cors
gem 'rack-cors', '~> 1.1', '>= 1.1.1'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  # Is a testing framework for Rails 5+. Read more: https://github.com/rspec/rspec-rails
  gem 'rspec-rails', '~> 5.0', '>= 5.0.2'
end

group :development do
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :test do
  # Provides integration between factory_bot and rails 5.0 or newer. Read more: https://github.com/thoughtbot/factory_bot_rails
  gem 'factory_bot_rails', '~> 4.11', '>= 4.11.1'
  # Provides RSpec- and Minitest-compatible one-liners to test common Rails functionality. Read more: https://github.com/thoughtbot/shoulda-matchers
  gem 'shoulda-matchers', '~> 5.0'
  # Port of Data::Faker from Perl, is used to easily generate fake data: names, addresses, phone numbers, etc. Read more: https://github.com/faker-ruby/faker
  gem 'faker', '~> 2.19'
  # A RuboCop extension for Faker. Read more: https://github.com/koic/rubocop-faker
  gem 'rubocop-faker', '~> 1.1'
  # Strategies for cleaning databases. Can be used to ensure a clean slate for testing. Read more: https://github.com/DatabaseCleaner/database_cleaner
  gem 'database_cleaner', '~> 2.0', '>= 2.0.1'
end
