source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.7"

# Rails
gem "rails", "~> 7.0.5"

# Asset pipeline
gem "sass-rails"
gem "sprockets-rails"

# Database
gem "mysql2"

# Web server
gem "puma", "~> 5.0"

# JS bundling
gem "jsbundling-rails"

# Hotwire
gem "turbo-rails"
gem "stimulus-rails"

# JSON APIs
gem "jbuilder"

# HTTP client
gem "rest-client"

# Fake data for testing
gem "faker"

# Pagination
gem "pagy"

# Friendly IDs
gem "friendly_id", "~> 5.4.0"

# Timezones
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

# Performance
gem "bootsnap", require: false

# Authorization
gem "pundit"

# HTML formatting
gem "htmlbeautifier"

# Debugging
gem "pry-byebug"

# Authentication
gem "devise"

# CSS autoprefixing
gem "autoprefixer-rails"

# Font icons
gem "font-awesome-sass", "~> 6.1"

# Forms
gem "simple_form", github: "heartcombo/simple_form"

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "dotenv-rails"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

# Cloudinary for image hosting
gem "cloudinary"
