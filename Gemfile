source "https://rubygems.org"

gem "rails", "4.0.0"
gem "mongoid", github: "mongoid/mongoid"
gem "sass-rails", "~> 4.0.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.0.0"
gem "therubyracer", platforms: :ruby
gem "jquery-rails"
gem "turbolinks"
gem "jbuilder", "~> 1.2"
gem "bootstrap-sass", "~> 3.0.2.0"
gem "font-awesome-sass-rails"
gem "simple_form"
gem "devise", "~> 3.0.0"
gem "cancan"
gem "omniauth"
gem "omniauth-facebook"
gem "omniauth-twitter"
gem "hashugar", github: "alex-klepa/hashugar"

group :development do
  gem "guard-rspec"
  gem "pry"
  gem "quiet_assets"
  gem "thin"
end

group :development, :test do
  gem "zeus"
  gem "rspec-rails"
  gem "factory_girl_rails"
end

group :test do
  gem "mongoid-rspec"
  gem "ffaker"
  gem "simplecov", require: false
  gem "database_cleaner"
  gem "rb-inotify", "~> 0.9"
end
