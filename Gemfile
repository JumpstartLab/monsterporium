source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'jquery-rails'
gem 'rake'
gem 'unicorn'
gem 'bootstrap-sass'
gem 'simple_form'
gem 'jquery-rails'
gem 'sorcery'
gem 'paperclip'
gem 'stripe', :git => 'https://github.com/stripe/stripe-ruby'
gem 'pg'
gem 'aws-sdk'

group :production do
  gem 'rack-google_analytics', :require => "rack/google_analytics"
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'cane'
  gem 'reek'
  gem 'debugger'
  gem 'capybara'
  gem 'simplecov'
end

group :test do
  gem 'faker'
  gem 'guard-rspec'
  gem 'launchy'
end