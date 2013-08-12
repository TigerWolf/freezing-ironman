source 'http://rubygems.org'
source 'https://gems.gemfury.com/fHtphqCq9zLeDRvssKD4/'

gem 'rails', '3.2.12'
gem 'rake',  '~> 0.9.2'

# HTTP server
gem 'unicorn', '~> 4.5.0'

# EngineYard
gem 'ey_config'
gem 'ey-provisioner', ">= 1.0.1"

# Error Capturing
gem 'airbrake'

# HTTP Client
gem "excon", "0.6.6" # TODO: Update this when we deprecate and remove cabinet (post FP migration)

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
gem 'settingcrazy', '~> 0.1.11', git: 'https://github.com/echannel/settingcrazy.git'
gem "acts_as_list", "~> 0.2.0"

# These required for seeds so is used in production (for staging/develop)
gem 'machinist', "~> 2.0"
gem 'forgery', "~> 0.5.0"

# Controllers
gem 'inherited_resources', "~> 1.4.0"

# Views
gem 'browser', "~> 0.1.5"
gem 'haml', "~> 3.1.7"
gem 'haml-rails', "~> 0.3.5"
gem 'will_paginate', "~> 3.0.3"
gem 'dotiw', "~> 1.1.1"
gem 'navigasmic', '~> 1.0.4'

# Authentication and authorisation
gem 'devise','~> 2.2.3'
gem 'devise_invitable', '~> 1.1.6'
gem 'cancan', "~> 1.6.8"

# Encoding
gem 'magic_encoding', "~> 0.0.2"

# Images
gem 'gravtastic', "~> 3.2.6"

# Worker
gem 'nokogiri', "~> 1.5.6"
gem 'savon', "~> 1.2.0"
gem "httparty", "~> 0.10.0"
gem 'cabinet'#, "~> 0.2.2"
gem 'resque', :git => 'git://github.com/resque/resque.git', ref: '7c20cc5972cba44aca0878580ef284bb75246b67'
gem 'god', "~> 0.13.1", :require => false
gem 'rubyzip', "~> 0.9.9", :require => 'zip/zip'
gem 'aws-s3', "~> 0.6.3"
gem 'multi_json', '~> 1.5.0'


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

# Inventories
gem 'feed_proxy_client', "0.0.9"

# Inventory Filters
gem 'htmlentities', "~> 4.3.1"

# Add logic between setting_values & publishing values (Decorator)
gem 'draper', "~> 0.18.0"

# Application Config
gem "app", "~> 1.0.3"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier',     '>= 1.0.3'
  gem 'jquery-rails', '~> 2.1.4'
end

gem 'asset_sync',   '~> 0.5.4'

group :development, :test, :staging do
  # Fixtures
  gem 'database_cleaner', "~> 0.9.1"
end

group :development do
  gem "better_errors", "~> 0.7.2" # git: 'git://github.com/TigerWolf/better_errors.git'
  gem "quiet_assets", "~> 1.0.1"
  gem "binding_of_caller", "~> 0.7.1"
  gem "thin", "~> 1.5.0"
  gem 'meta_request', '0.2.1'
  # Live reloading
  gem 'guard-livereload', require: false
  gem 'rack-livereload'
  gem 'rb-fsevent',       require: false
  # Better logging
  gem 'sql-logging'
end

# Testing
group :development, :test do
  # Rspec
  gem 'rspec-rails', '>= 2.12.0'
  gem 'shoulda', "~> 3.3.2"

  # Moving over to FactoryGirl
  gem "factory_girl_rails", "~> 4.2.1", require: false

  gem 'capybara', "~> 1.1.4" # 2.0 is now avaliable - will need to check this and possibly upgrade
  gem 'capybara-webkit', "~> 0.12.0"
  gem 'capybara-firebug', "~> 1.3.0"
  gem 'selenium-client', "~> 1.2.18"
  gem 'selenium-webdriver', '2.31.0'

  gem 'poltergeist'

  # Mocking
  gem "mocha", "~> 0.13.2", :require => "mocha/setup"

  # Helpers
  gem 'timecop', "~> 0.6.2.2"
  gem 'timer', '~> 0.1.6'

  gem "spork", "~> 0.9.2"
  gem 'pry', " ~> 0.9.12.2"
  gem 'pry-rails', "~> 0.3.0"
  gem 'pry-rescue', '~> 1.1.1'
  gem 'pry-stack_explorer', "~> 0.4.9"
  gem 'sham_rack', "~> 1.3.4"

  gem 'hirb', "~> 0.7.0"

  # Fake mail for development
  gem 'mailtrap', "~> 0.2.1"

  # VCR Mocks
  gem "vcr", "~> 2.3.0"
  gem "fakeweb", "~> 1.3.0"

  gem "launchy", "~> 2.1.2"

  # Coverage Testing in the cloud :p
  gem 'coveralls', require: false
  gem 'simplecov', :require => false
end

group :test do
  gem 'resque_spec', "~> 0.13"
end
