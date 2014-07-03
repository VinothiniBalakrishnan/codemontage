source 'https://rubygems.org'
ruby "2.0.0"

# Admin Tools
gem 'activeadmin'
gem 'meta_search',    '>= 1.1.0.pre'

# Baseline Infrastructure
gem 'rails', '3.2.18'
gem 'jquery-rails'
gem 'pg'
gem 'psych'

# Operations
gem 'newrelic_rpm', '~> 3.7.1.182'

# Users & Authentication
gem 'bcrypt-ruby', require: 'bcrypt' 
gem 'devise', '~> 2.2.8'
gem 'omniauth'
gem 'omniauth-github'
gem 'simple_form'

# Data & Features
gem 'acts-as-taggable-on', '~> 2.3.1'
gem 'friendly_id', '~> 4.0.10'
gem 'geocoder'
gem 'gmaps4rails'
gem 'paperclip', '~> 3.0'
gem 'aws-sdk'

# Test Suite
group :development, :test do 
  gem 'rspec-rails'
  gem 'capybara'
end

group :test do
  gem 'shoulda-matchers'
  gem 'simplecov'
end

# Development helpers
group :development do
  gem 'quiet_assets'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # Foundation front-end framework
  gem 'compass-rails'
  gem 'zurb-foundation', '~> 4.0.0'
  gem 'uglifier', '>= 1.0.3'
end
