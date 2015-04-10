source "https://rubygems.org"

gem "rails", "4.1.8"

gem "unicorn"

gem "mysql2", ">= 0.3.14"

# uncomment to use PostgreSQL
# gem "pg"
#
# NOTE: If you use PostgreSQL, you must still leave enabled the above mysql2
# gem for Sphinx full text search to function.

gem "thinking-sphinx", "~> 3.1.2"

gem "uglifier", ">= 1.3.0"
gem "jquery-rails"
gem "dynamic_form"

gem "exception_notification"

gem "bcrypt", "~> 3.1.2"

gem "nokogiri", "= 1.6.1"
gem "htmlentities"
gem "rdiscount"

# for twitter-posting bot
gem "oauth"

# for parsing incoming mail
gem "mail"

group :test, :development do
  # Use Capistrano for deployment
  gem 'capistrano', '~> 3.1.0'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-rvm'
  gem 'capistrano-bundler', '>= 1.1.2'
  gem 'capistrano-ext'
  gem 'capistrano3-puma'

  gem "rspec-rails", "~> 2.6"
  gem "machinist"
  gem "sqlite3"
  gem "faker"
end

group :production do
  gem 'puma'
end
