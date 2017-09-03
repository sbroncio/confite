
source 'https://rubygems.org'

gem 'rails', '~> 5.1.3'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby
gem 'annotate'
gem 'paginate'
gem "awesome_print", require:"ap"
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
# gem 'redis', '~> 3.0'
gem 'bcrypt', '~> 3.1.7'


# gem 'capistrano-rails', group: :development
group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'capybara-webkit'
  gem 'database_cleaner'
  gem 'byebug', platform: :mri
  gem 'shoulda-matchers'
  gem 'spring-commands-rspec'
  gem 'headless'
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem "pry-rails"
  gem 'pry-doc'
  gem 'brakeman', :require => false
end

group :test do
  gem "selenium-webdriver"
  gem 'ci_reporter'
  gem 'ci_reporter_rspec'
  gem 'rspec_junit_formatter'
  gem 'simplecov', :require => false
  gem 'simplecov-json', :require => false
  gem 'simplecov-rcov', :require => false
end 
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
#gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
