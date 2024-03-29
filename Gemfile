source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.2'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.4.4'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'devise'

# for View
gem 'haml-rails'
gem 'gretel'
gem 'kaminari'
gem 'kaminari-bootstrap', '~> 3.0.1'

# for Form
gem 'ransack'
gem 'simple_form'
gem 'cocoon'

# for Model
gem 'paranoia'
gem 'draper'
gem 'pundit'
gem 'paper_trail'
gem 'request_store'

# for Async
gem 'sidekiq'
gem 'sidekiq-cron'

# for File Upload
gem 'fog-aws'
gem 'aws-sdk-s3'
gem 'carrierwave'

group :development, :test do
  gem 'dotenv-rails', require: 'dotenv/rails-now'

  # for Debug
  gem 'byebug', platforms: %i(mri mingw x64_mingw)
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-byebug'
  gem 'better_errors'
  gem 'binding_of_caller'

  # for Static Code Analysis
  gem 'rubocop'
  gem 'rubocop-rspec-focused', require: false
  gem 'rails_best_practices'
  gem 'brakeman', require: false
  gem 'bullet'
end