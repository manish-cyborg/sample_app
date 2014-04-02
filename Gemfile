#source 'https://rubygems.org'

#gem 'rails', '3.2.15'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

#gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
#group :assets do
#  gem 'sass-rails',   '~> 3.2.3'
#  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

 # gem 'uglifier', '>= 1.0.3'
#end

#gem 'jquery-rails'

# To use ActiveModel has_secure_password
 gem 'bcrypt-ruby', '~> 3.0.1'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
source 'https://rubygems.org'
ruby '1.9.3'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '3.2.15'
gem 'pg', '0.15.1'
gem 'sqlite3'

group :development, :test do
  #gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec', '2.5.0'
  gem 'spork-rails', '4.0.0'
  gem 'guard-spork', '1.5.0'
  gem 'childprocess', '0.3.6'
end

group :test do
  gem "mocha", :require => false
  gem 'test_after_commit'
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
end
#gem 'capybara', '2.1.0'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'
gem 'bootstrap-sass', '2.3.2.0'
gem 'sprockets'
gem 'factory_girl'
gem 'strong_parameters'
# group :doc do
#   gem 'sdoc', '0.3.20', require: false
# end

group :production do
  gem 'rails_12factor', '0.0.2'
end