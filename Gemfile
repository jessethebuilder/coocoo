source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'bootstrap-sass', '~> 3.0.3.0'

gem 'devise'
#gem 'geocoder'

gem 'carrierwave'
gem 'fog'
gem 'bootsy'
gem 'mini_magick'

# eCommerce
gem 'shoppe', '~> 1.0'
gem "shoppe-paypal"
gem "shoppe-stripe", require: "shoppe/stripe"

gem 'meta_farm', '0.0.1', :git => 'https://github.com/jessethebuilder/meta_farm'
# gem 'meta_farm', '0.0.1', :path => 'c:/users/bucky/desktop/jesseweb/meta_farm'

gem 'sdad', '0.0.1', :git => 'https://github.com/jessethebuilder/sdad'

# gem 'farm_shed', '0.0.2', :path => 'C:\Users\Bucky\Desktop\jesseweb\farm_shed'
gem 'farm_shed', '0.0.2', :git => 'https://github.com/jessethebuilder/farm_shed'

gem 'farm_slugs', :git => 'https://github.com/jessethebuilder/farm_slugs'

group :test, :development do
  gem 'faker'
  gem 'rspec-rails'
  gem 'wdm'
  gem 'database_cleaner', '~> 1.0.0rc'
  gem 'timecop'
end

group :test do
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'guard-rspec'
  gem 'selenium-webdriver'
  gem 'shoulda'
  gem 'launchy', '~> 2.3.0'
  #gem 'webrat'
end

group :production do
  gem 'rails_12factor'
  gem 'faker'
end

