source 'https://rubygems.org'
ruby '2.3.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
# Use sqlite3 as the database for Active Record in dev/test
gem 'sqlite3', group: [:development, :test]
# Use PostgreSQL in production
gem 'pg', group: :production
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Bootstrap for stylesheet
gem 'bootstrap-sass', '~> 3.3'
# Use Font Awesome icons for buttons
gem 'font-awesome-rails', '~> 4.3'
# Use Simple Form for rendering forms
gem 'simple_form', '~> 3.1.0'
# Use Devise for authenticating users
gem 'devise', '~> 3.4.1'
# Use Pundit for user permissions
gem 'pundit', '~> 0.3.0'
# Use CarrierWave for uploading files
gem 'carrierwave', '~> 0.10.0'
# Use Searcher for search
gem 'searcher', github: 'radar/searcher'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use AMS for serializing models
gem 'active_model_serializers', '~> 0.9.3'

# Use Fog for files upload
gem 'fog', '~> 1.36.0'

# Use 12factor for logging and static assets
gem 'rails_12factor', group: :production

# Use Puma server for production
gem 'puma', group: :production

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Use RSpec for testing
  gem 'rspec-rails', '~> 3.4.1'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # Thin server
  gem 'thin'
end

group :test do
  gem 'capybara', '~> 2.4'
  gem 'factory_girl_rails', '~> 4.5'
  gem 'selenium-webdriver', '~> 3.0.0'
  gem 'database_cleaner', '~>  1.4'
  gem 'email_spec', '~> 1.6.0'
end
