source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.3"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4"
gem 'rails-i18n', '~> 7.0', '>= 7.0.6'

gem "slim-rails"

gem 'sidekiq', '~> 7.0', '>= 7.0.2'
gem 'sinatra', github: 'sinatra/sinatra', require: nil
gem 'sidekiq-statistic'

gem 'gravatar_image_tag'
gem 'country_select'
gem 'kaminari', '~> 1.2', '>= 1.2.1'

gem 'money-rails', '~> 1.7'

gem 'ransack'

gem 'slack-notifier'

gem 'premailer-rails', '~> 1.7'

gem 'griddler'

gem 'griddler-mailgun', '~> 1.1', '>= 1.1.1'

gem 'rollbar'
# Devise Authentication
gem "devise", "~> 4.8"

# https://github.com/scambra/devise_invitable - gem install devise_invitable
gem 'devise_invitable', '~> 2.0.0'

# Very simple Roles library without any authorization enforcement supporting scope on resource objects (instance or class). Supports ActiveRecord and Mongoid ORMs.
gem 'rolify', '~> 6.0'

# Continuation of the simple authorization solution for Rails which is decoupled from user roles. All permissions are stored in a single location.
gem 'cancancan', '~> 1.15'

gem 'paper_trail'

# Simple URLs with human-friendly strings
gem 'friendly_id', '~> 5.4', '>= 5.4.2'

# CoffeeScript adapter for the Rails asset pipeline
gem 'coffee-rails', '~> 5.0'

# This gem provides jQuery and the jQuery-ujs driver for your Rails 4+ application.
gem 'jquery-rails', '~> 4.4'

# Turbolinks makes following links in your web application faster (use with Rails Asset Pipeline)
gem 'turbolinks', '~> 2.5', '>= 2.5.3'

# AASM is a continuation of the acts-as-state-machine rails plugin, built for plain Ruby objects.
gem 'aasm', '~> 5.2'

gem 'lodash-rails', '~> 4.17', '>= 4.17.21'

# Uglifier minifies JavaScript files by wrapping UglifyJS to be accessible in Ruby
gem 'uglifier', '~> 2.7', '>= 2.7.2'
# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"

gem 'local_time', '~> 1.0', '>= 1.0.3'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
gem "sassc-rails"
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'rspec-rails', '~> 3.5'
end

gem 'simplecov', :require => false, :group => :test
gem "factory_bot_rails", "~> 4.0"

group :development do
  gem "letter_opener"
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'capybara'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'rack-cors', :require => 'rack/cors'

end

