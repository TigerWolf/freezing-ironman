source 'http://rubygems.org'
source 'https://gems.gemfury.com/fHtphqCq9zLeDRvssKD4/'

gem 'rails', '3.2.8'
gem 'rake',  '~> 0.9.2'

# HTTP server
gem 'unicorn', '~> 4.4.0'

# Performance
gem 'rpm_contrib', '~> 2.1.4'
gem 'newrelic_rpm', '~> 3.5.3'

# Models
gem 'pg', '>= 0.11.0'
gem "squeel", "~> 1.0.14"
gem 'meta_search', "~> 1.1.3"
gem 'valium', "~> 0.5.0"
gem 'ancestry', "~> 1.3.0"
gem "nickel", "~> 0.0.6"
gem 'activerecord-import', "~> 0.2.11"
gem 'settingcrazy', '~> 0.1.7', git: 'https://github.com/echannel/settingcrazy.git'

# These required for seeds so is used in production (for staging/develop)
# gem 'sham'
gem 'machinist', "~> 2.0"
gem 'forgery', "~> 0.5.0"

# Controllers
gem 'inherited_resources', "~> 1.3.1"

# Views
gem 'browser', "~> 0.1.5"
gem 'haml', "~> 3.1.7"
gem 'haml-rails', "~> 0.3.5"
gem 'will_paginate', "~> 3.0.3"
gem 'dotiw', "~> 1.1.1"

# Authentication and authorisation
gem 'devise','~> 2.1'
gem 'devise_invitable', '~> 1.1.4'
gem 'cancan', "~> 1.6.8"

# Encoding
gem 'magic_encoding', "~> 0.0.2"

# Images
gem 'gravtastic', "~> 3.2.6"

# Worker
gem 'nokogiri', "~> 1.5.6"
gem 'savon', "~> 1.2.0"
gem 'httparty', "~> 0.9.0"
gem 'cabinet'#, "~> 0.2.2"
gem 'resque', :git => 'git://github.com/defunkt/resque.git'
gem 'god', "~> 0.13.1", :require => false
gem 'rubyzip', "~> 0.9.9", :require => 'zip/zip'
gem 'aws-s3', "~> 0.6.3"
gem 'multi_json', '~> 1.3.7'

# Documentation
gem 'yard', "~> 0.8.3"

# Email
gem "aws-ses", "~> 0.4.4", :require => 'aws/ses'

# SFTP (for Grays SFTP access)
gem "net-sftp", "~> 2.0.5"

# Data Migration
gem 'data_migrate', "~> 1.2.0", git: 'git://github.com/doublewide/data-migrate.git'

# Notifications
gem 'notification_client'

# Inventory Filters
gem 'htmlentities', "~> 4.3.1"

# LEAVE IN PRODUCT - USED FOR CONVERSION CODE CHECKER
# Capybara
gem 'capybara', "~> 1.1.4" # 2.0 is now avaliable - will need to check this and possibly upgrade
gem 'capybara-webkit', "~> 0.13.0"

# Add logic between setting_values & publishing values
gem 'draper', "~> 0.18.0"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier',     '>= 1.0.3'
  gem 'jquery-rails', '~> 2.1.4'
end

group :development, :test, :staging do
  # Fixtures
  gem 'database_cleaner', "~> 0.9.1"
end

group :development do
  gem "better_errors", git: 'git://github.com/TigerWolf/better_errors.git'
  gem "quiet_assets", "~> 1.0.1"
  gem "binding_of_caller"
  gem "thin", "~> 1.5.0"
end

# Testing
group :development, :test do
  # Rspec
  gem 'rspec-rails', '>= 2.6.0'
  gem 'fuubar', "~> 1.1.0"
  gem 'shoulda', "~> 3.3.2"

  # Used for continuous deployment
  #gem "engineyard", "2.0.9"

  gem 'capybara-firebug', "~> 1.3.0"
  gem 'selenium-client', "~> 1.2.18"
  gem 'selenium-webdriver', '2.27.2'

  gem 'poltergeist'

  # Mocking
  gem "mocha", "~> 0.11.4" #new versions have updates for mini-test - not needed for now (0.13)

  # Helpers
  gem 'timecop', "~> 0.5.3"
  gem 'timer', '~> 0.1.6'

  gem "spork", "~> 0.9.2"
  gem 'pry', " ~> 0.9.10 "
  gem 'sham_rack', "~> 1.3.4"
  gem "ruby-debug19", "~> 0.11.6"

  gem 'hirb', "~> 0.7.0"

  # Fake mail for development
  gem 'mailtrap', "~> 0.2.1"

  # VCR Mocks
  gem "vcr", "~> 2.3.0"
  gem "fakeweb", "~> 1.3.0"

  gem "launchy"
end

group :test do
  gem 'resque_spec', "~> 0.12.5"
end
