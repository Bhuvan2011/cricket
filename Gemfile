source 'https://rubygems.org'

gem 'rails', '3.2.8'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

#gem 'sqlite3', '~> 1.3.6'

gem 'twitter-bootstrap-rails', '~> 2.1.3'
gem 'therubyracer', '~> 0.10.2'

group :production , :staging do
  gem 'pg', '0.12.2'
end

group :development, :test do
  gem "sqlite3-ruby", "~> 1.3.0", :require => "sqlite3"
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
  gem 'less-rails'
end

gem 'jquery-rails'

gem 'simple_form'

gem 'devise'
gem 'omniauth-facebook', '1.4.0' # There is an issue with 1.4.1: http://stackoverflow.com/questions/11597130/omniauth-facebook-keeps-reporting-invalid-credentials


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
