source 'http://rubygems.org'

gem 'rails', '3.1.3'

gem 'rails-backbone'

gem "haml-rails"

gem 'jquery-rails'

group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'twitter-bootstrap-rails'
end

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'pg'
  gem 'guard-rspec'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'launchy'
  # Pretty printed test output
  gem 'turn', '0.8.2', :require => false
  gem 'cucumber'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
end
