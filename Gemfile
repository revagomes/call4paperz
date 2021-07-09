source 'http://rubygems.org'
ruby '1.9.3'

gem 'addressable'
gem 'carrierwave', github: 'jnicklas/carrierwave'
gem 'devise', '>= 3.0.0'
gem 'devise-encryptable', '>= 0.1.1'
gem 'fog'
gem 'friendly_id'
gem 'jquery-rails', '>= 2.2.1', '>= 2.2.1'
gem 'jquery-rails'
gem 'mail_form'
gem 'mini_magick'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-oauth2'
gem 'omniauth-twitter'
gem 'pg'
gem 'rails', '4.0.0'
gem 'rake'
gem 'recaptcha', :require => 'recaptcha/rails'
gem 'responders', '1.0.0'
gem 'unicorn'
gem 'validates_timeliness', '~> 3.0.14'
gem 'will_paginate'

group :production do
  gem 'newrelic_rpm'
end

group :assets do
  gem 'compass-rails'
  gem 'sass-rails', '~> 4.0.0'
  gem 'uglifier'
end

group :development do
  gem 'better_errors'
  gem 'bullet'
  gem "thin"
end

group :development, :test do
  gem 'pry-meta'
  gem 'foreman'
  gem 'rspec-rails', '>= 2.13.0'
end

group :test do
  gem 'capybara'
  gem 'culerity'
  gem 'database_cleaner'
  gem 'factory_girl_rails', '>= 4.2.1'
  gem 'sqlite3'
  gem 'timecop'
  gem 'shoulda-matchers'
end
