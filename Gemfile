source 'http://rubygems.org'

gem 'rails', '3.0.7'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano', :group => :development

group :development, :test do
  # To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
  gem 'ruby-debug', :platforms => :ruby_18
  gem 'ruby-debug19', :require => 'ruby-debug', :platforms => :ruby_19
end

group :production do
  gem 'dalli'
  gem 'spree_heroku', :group => :production
end

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end

gem 'russian'
gem 'spree', '~> 0.60.0'
gem 'spree_i18n', :git => 'git://github.com/spree/spree_i18n.git'
gem 'spree_static_content'
gem 'spree_editor'
gem 'spree_online_support'
gem 'spree_robokassa'
gem 'spree_yandex_market'
gem 'spree_address_book'
gem 'spree_dynamic_sitemaps'
gem 'synergy', '~> 0.50.0'
gem 'synergy_default_theme', '1.0.1'
