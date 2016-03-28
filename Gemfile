source 'https://rubygems.org'

ruby '2.3.0'

gem 'rails', '4.2.6'

gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'mysql2', '>= 0.3.13', '< 0.5'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks'
gem 'uglifier', '>= 1.3.0'

gem 'active_model_serializers'
gem 'figaro'

group :doc do
  gem 'sdoc', '~> 0.4.0'
end

group :development do
  gem 'annotate'
  gem 'guard-rspec', require: false
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'terminal-notifier-guard'
  gem 'web-console', '~> 2.0'
end

group :development, :test do
  gem 'byebug'
  gem 'database_rewinder'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'rspec-rails'
end

group :test do
  gem 'json_spec'
  gem 'rspec-request_describer'
end

group :production do
  gem 'rails_12factor'
end
