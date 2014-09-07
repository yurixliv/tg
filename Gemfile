source 'https://rubygems.org'

ruby '2.1.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0.rc1'

# database
gem 'mysql2', '0.3.11'

# controllers
gem 'inherited_resources', '1.4.1'
gem 'has_scope', '0.6.0rc'

# server
gem 'unicorn'

# assets
gem 'sass-rails', '4.0.1'
gem 'uglifier'
gem 'jquery-rails'
# gem 'js-routes', '0.9.6'

# view
gem 'slim-rails', '2.0.1'
gem 'bootstrap-sass', '2.3.2'
gem "slim", '2.0.2'
# gem 'codus', '0.0.1.7.1'
gem 'jbuilder', '2.0.3'
gem 'bootstrap-datepicker-rails', '~> 1.3.0.1'

# authentication
# gem 'devise', '3.2.3'

# development helpers and tests
group :development, :test do
  gem 'thin'
  gem 'quiet_assets'
  gem 'debugger'
  gem 'dotenv-rails'
  gem 'spring-commands-rspec'
  gem 'factory_girl_rails'
end

group :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'database_cleaner'
end


group :production, :staging do
  gem 'rails_12factor', '0.0.2'
  gem 'newrelic_rpm'
  gem 'newrelic-redis'
end
