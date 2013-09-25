source "https://rubygems.org"
ruby "1.9.3"

gem 'rails', '3.2.3'
gem 'jquery-rails'
gem 'turbolinks'

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'sqlite3'
end

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'bootstrap-sass', '~> 2.2.2.0'
  gem 'rails_12factor', group: :production
  # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end


