# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "rails", "~> 7.0.0"
gem "omniauth"
gem "omniauth-oauth2"
gem "rdoc"

gem "rails-controller-testing", github: "rails/rails-controller-testing"

gem "responders", "~> 3.0"

group :test do
  gem "nokogiri", "< 1.13"
  gem "omniauth-facebook"
  gem "omniauth-openid"
  gem "rexml"
  gem "timecop"
  gem "webrat", "0.7.3", require: false
  gem "mocha", "~> 1.1", require: false
end

platforms :ruby do
  gem "sqlite3", "~> 1.4"
end

gem "tzinfo-data"

# platforms :jruby do
#   gem "activerecord-jdbc-adapter"
#   gem "activerecord-jdbcsqlite3-adapter"
#   gem "jruby-openssl"
# end

# TODO:
# group :mongoid do
#   gem "mongoid", "~> 4.0.0"
# end
