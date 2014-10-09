source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.4'

# Assets
gem 'active_model_serializers'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]

# Persistence
gem 'tiny_tds', platforms: [:mingw, :mswin]
gem 'activerecord-sqlserver-adapter'
gem 'ruby-oci8', '~> 2.1.7', platforms: [:mingw, :mswin]
gem 'pg', platforms: 'ruby'

# Authentication 
gem 'cancancan'
gem 'net-ldap', :require => 'net/ldap'
gem 'rack'
gem 'ruby-saml'

group :development do
  gem 'guard-livereload', require: false
  gem 'thin'
  gem 'better_errors'
  gem 'meta_request'
  gem 'yaml_db', github: 'jetthoughts/yaml_db'
end

group :development, :test do
  gem 'pry-rails'
  gem 'rspec-rails', '~> 3.1.0'
  gem 'guard-rspec'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
end
