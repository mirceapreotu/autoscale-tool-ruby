source 'https://rubygems.org'

gem 'rails', '3.2.9'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

# AWS requirements
gem 'aws-sdk'
gem 'uuidtools', '~> 2.1'
gem 'httparty', '~> 0.7'
gem 'nokogiri', '>= 1.4.4'
gem 'json', '>= 1.4.6'
gem 'net-ssh', '~> 2.6.2'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development do
  gem 'yard'
  gem 'pry'
end

group :test do
  gem 'rspec'
  gem 'simplecov', :require => false
  gem 'rvm-tester'
  gem 'cucumber', '~> 0.10.2', :require => 'cucumber/rake/task'
  gem 'bourne', '1.0'
  gem 'mocha', '0.9.8'
  gem 'multipart-post', '~> 1.1.2'
  gem 'rotp', '~> 1.3.0'
  gem 'jruby-openssl', :platforms => :jruby
end