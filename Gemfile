source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'
# Use PostgreSQL as the database for Active Record
gem 'pg'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'bootstrap', '~> 4.0.0.beta2.1'
gem 'font-awesome-rails'
gem 'bootstrap-social-rails'
gem 'jquery-rails'

# Easy upload management for ActiveRecord
gem 'paperclip', '~> 5.2.0'
# User Authentication
gem 'devise'
gem 'omniauth-google-oauth2'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

group :development, :test do
  gem 'pry-nav'             # Debugger with 'next', 'continue' options
  gem 'dotenv-rails'
  gem 'rspec-rails'
end

group :test do
  gem 'capybara'            # User simulations
  gem 'factory_girl_rails'  # Fixtures
  gem 'guard-rspec'         # Runs specs automatically after saves
  gem 'database_cleaner'
  gem 'rails-controller-testing'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do # Heroku requirements
  gem 'newrelic_rpm'        # App performance monitoring
  gem 'rails_12factor'      # Avoid Heroku deprecation warning
end