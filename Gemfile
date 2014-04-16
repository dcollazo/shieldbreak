source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.1.0'

gem 'bourbon'
gem 'neat'
gem 'normalize-rails'

gem 'bcrypt-ruby'
gem 'faker'

gem 'rename'

gem 'spring',        group: :development

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec'
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'cucumber-rails'
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
  
  gem 'growl', '1.0.3'
  
  # Uncomment on Linux
  # gem 'libnotify', '0.8.0'
end

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'

gem 'sdoc', '~> 0.4.0',          group: :doc

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
