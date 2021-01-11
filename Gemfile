source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.1'

gem 'rails', '~> 6.0.2', '>= 6.0.2.1'

gem 'bootsnap', '>= 1.4.6', require: false
gem 'bootstrap', '~> 4.3', '>= 4.3.1'
gem 'clearance', '1.16.1'
gem 'font-awesome-sass', '~> 5.12.0', '>= 5.12.0'
gem 'metainspector'
gem 'pagy', '~> 2.1.2'
gem 'pg', '~> 0.18'
gem 'puma', '~> 4.3'
gem 'redcarpet', '~> 3.5.1'
gem 'rouge'
gem 'sass-rails', '>= 6'
gem 'slim-rails', '~> 3.2.0'
gem 'turbolinks', '~> 5.2.0'
gem 'uglifier'
gem 'webpacker', '~> 5.1.1'

group :development, :test do
  gem 'byebug', platforms: %i(mri mingw x64_mingw)
  gem 'factory_bot_rails'
  gem 'faker', '~> 1.9.1'
  gem 'rspec-rails', '~> 4.0.0'
end

group :development do
  gem 'bullet', '~> 6.1'
  gem 'guard-livereload', '~> 2.5', require: false
  gem 'guard-rspec', require: false
  gem 'guard-rubocop', require: false
  gem 'guard'
  gem 'letter_opener'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'pry-awesome_print'
  gem 'pry-rails'
  gem 'rack-livereload'
  gem 'rubocop-performance'
  gem 'rubocop-rspec', require: false
  gem 'rubocop', '~> 0.67.2', require: false
  gem 'simplemde-rails'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'spring'
  gem 'web-console', '>= 3.7.0'
end

group :test do
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'rspec_junit_formatter'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers', '~> 4.3.0'
  # Workaround for cc-test-reporter with SimpleCov 0.18.
  # Stop upgrading SimpleCov until the following issue will be resolved.
  # https://github.com/codeclimate/test-reporter/issues/418
  gem 'simplecov', '~> 0.10', '< 0.18'
  gem 'webdrivers'
end
