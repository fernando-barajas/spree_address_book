source "http://rubygems.org"
gemspec

gem 'pry'
gem 'rails-pry'
gem 'pry-debugger'

group :test do
  gem 'sass-rails',   '~> 4.0.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'selenium-webdriver'

  if RUBY_PLATFORM.downcase.include? "darwin"
    gem 'rb-fsevent'
    gem 'growl'
    gem 'guard-rspec'
  end
end

gem 'devise'
gem 'devise-encryptable'
gem 'spree_auth_devise', :git => 'git://github.com/spree/spree_auth_devise', :branch => '2-1-stable'
gem 'spree', '2.1.4'
