source 'https://rubygems.org'

# Specify your gem's dependencies in roadie-rails.gemspec
gemspec

# Additional development dependencies I use but don't want to declare in the
# gemfile since they aren't required to develop this codebase.
if RUBY_VERSION >= "2.3.0"
  group :development do
    gem 'guard'
    gem 'guard-rspec'
  end
else
  gem "rails", ">= 3.0", "<= 5.1"
end

# Added here so it does not show up on the Gemspec; I only want it for CI builds
gem 'codecov', group: :test, require: false
