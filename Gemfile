source "https://rubygems.org"

ruby "2.5.5"
#ruby-gemset=pghero

gem "rails", "~> 5.2.0"

gem 'pg'

gem "pghero" #, git: "https://github.com/ankane/pghero.git"
gem "pg_query"
gem "aws-sdk-cloudwatch"
gem "puma"
gem "activerecord-nulldb-adapter", require: false
gem "tzinfo-data"

source 'https://gems.outoforder.cc/' do
  gem 'hubstaff_auth', '~> 0.16.0'
  # gem 'hubstaff_auth', path: '../hubstaff_auth'
end

group :development do
  gem 'dotenv-rails'
  gem 'awesome_print'
end
