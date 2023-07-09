source "https://rubygems.org"

ruby "3.2.2"

gem "rails", "~> 7.0.5"

gem "bootsnap", require: false # Reduces boot times through caching
gem "pg"                       # Use postgresql as the database for Active Record
gem "puma"                     # Use the Puma web server [https://github.com/puma/puma]
gem "redis"                    # Use Redis for Action Cable

# Assets
gem "importmap-rails"   # Use JavaScript with ESM import maps
gem "sprockets-rails"   # The original asset pipeline for Rails
gem "stimulus-rails"    # Hotwire's modest JavaScript framework
gem "tailwindcss-rails" # Use Tailwind CSS with Rails
gem "turbo-rails"       # Hotwire's SPA-like page accelerator

group :development, :test do
  gem "brakeman"           # A static analysis security vulnerability scanner
  gem "bundle-audit"       # Patch-level verification for Bundler
  gem "capybara"           # Acceptance test framework for web applications
  gem "debug"              # A simple and easy to use debug helper for Ruby
  gem "minitest-rails"     # Minitest integration for Rails
  gem "minitest-reporters" # Create customizable Minitest output formats
  gem "pry"                # An IRB alternative and runtime developer console
  gem "selenium-webdriver" # Browser automation framework and ecosystem
  gem "standard"           # Ruby Style Guide, with linter & automatic code fixer
  gem "standard-rails"     # Ruby on Rails Style Guide
  gem "webdrivers"         # Run Selenium tests more easily
end

group :development do
  gem "rack-mini-profiler" # Add speed badges
end
