source "https://rubygems.org"

gem "rails", "~> 8.0.2"

gem "propshaft"

gem "sqlite3", ">= 2.1"

gem "puma", ">= 5.0"

gem "importmap-rails"

gem "turbo-rails"

gem "stimulus-rails"

gem "tailwindcss-rails"

gem "jbuilder"

gem "tzinfo-data", platforms: %i[ windows jruby ]

gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "devise"
gem "simple_form"
gem "bootsnap", require: false

gem "kamal", require: false

gem "thruster", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "awesome_print"
  gem "dotenv-rails"
  gem "faker"
  gem "pry-rails"
  gem "factory_bot_rails"
  gem "rspec-rails"
  gem "rubocop"
  gem "brakeman", require: false

  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "database_cleaner"
  gem "webdrivers"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "simplecov"
  gem "vcr"
end
