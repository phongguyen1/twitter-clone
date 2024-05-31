source "https://rubygems.org"

ruby "3.2.3"

gem "bootsnap", require: false
gem "cssbundling-rails"
gem 'devise'
gem "jbuilder"
gem "jsbundling-rails"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "rails", "~> 7.1.3", ">= 7.1.3.3"
gem "redis", "~> 4.0"
gem "sass-rails"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "importmap-rails"
gem 'dotenv-rails', groups: [:development, :test]


group :development, :test do
  # gem "debug", platforms: %i[ mri windows ]
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  
  gem "factory_bot_rails"
  gem "faker", git: "https://github.com/faker-ruby/faker.git", branch: "main"
  gem "pry-rails"
  gem "rspec-rails", "~> 6.0.0"
end

group :development do
  gem "web-console"
end

group :test do
  gem "shoulda-matchers", "~> 5.0"
end
