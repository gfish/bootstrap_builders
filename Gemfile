source "https://rubygems.org"

# Declare your gem's dependencies in bootstrap_builders.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

group :development do
  gem "spring-commands-rspec", "1.0.4"
  gem "spring-commands-rubocop", "0.1.0"
end

group :development, :test do
  gem "devise", "3.5.6"
  gem "sqlite3", "1.3.11"
  gem "cancancan", "1.13.1"

  gem "best_practice_project", "0.0.9"
  gem "rubocop", "0.40.0"
end

group :test do
  gem "rspec-rails", "3.5.2"
  gem "factory_girl_rails", "4.7.0"
  gem "haml", ">= 4.0.7"
  gem "spring", "1.6.4"
  gem "simple_form", "3.3.1"
  gem "capybara", "2.6.2"
  gem "capybara-webkit", "1.8.0"
end

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use a debugger
# gem 'byebug', group: [:development, :test]
