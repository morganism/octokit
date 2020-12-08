# frozen_string_literal: true

source 'https://rubygems.org'

gem "octokit", "~> 4.0"

# when stdlib items become gems, they need to be added
install_if -> { RUBY_VERSION >= '2.8' } do
  gem 'rss', '>= 0.2.9'
end

group :development do
  gem 'awesome_print', require: 'ap'
  gem 'yard'
end
