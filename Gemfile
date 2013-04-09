source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0.beta1'
gem 'bootstrap-sass'
gem 'bcrypt-ruby'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec'
  gem 'spork-rails', github: 'A-gen/spork-rails'
  gem 'guard-spork'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara', '2.1.0.beta1'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'

  # Uncomment these lines on OS X.
  # gem 'rb-fsevent', '0.9.3', :require => false
  # gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  gem 'rb-inotify'
  gem 'libnotify'

  # Uncomment these lines on Windows.
  # gem 'rb-fchange', '0.0.6'
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
end

group :assets do
  gem 'sass-rails',   '4.0.0.beta1'
  gem 'coffee-rails', '4.0.0.beta1'
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :production do
  gem 'pg'
end