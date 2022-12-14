# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

gem 'jbuilder'
gem 'mini_racer', platforms: :ruby
gem 'puma'
gem 'rails', '~> 7.0.1'
gem 'react_on_rails'
gem 'shakapacker'
gem 'sprockets-rails'
gem 'pg'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'guard'
  gem 'guard-minitest'
end

group :development do
  gem 'brakeman'
  gem 'foreman'
  gem 'rubocop'
  gem 'rubocop-rails'
  gem 'spring'
end

group :test do
  gem 'factory_bot'
  gem 'faker'
  gem 'minitest-reporters'
  gem 'shoulda'
  gem 'simplecov'
  gem 'simplecov-lcov'
end
