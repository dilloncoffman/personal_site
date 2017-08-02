source 'https://rubygems.org'

ruby '2.4.1'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.0'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'pygments.rb', '~> 1.1.2'
gem 'redcarpet', '~> 3.4.0'
gem 'friendly_id', '~> 5.2', '>= 5.2.1'
gem 'will_paginate', '~> 3.1', '>= 3.1.5'
gem 'mail_form', '~> 1.6'
gem 'actionmailer', '~> 5.0.0'
gem 'rails-ujs', '~> 0.1.0'
gem 'devise', '~> 4.3'
gem 'passenger', '~> 5.1', '>= 5.1.4'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

gem 'sqlite3', :group => [:development, :test]
group :production do
  gem 'thin'
  gem 'pg'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # gem 'spring'
  # gem 'spring-watcher-listen', '~> 2.0.0' 
end


group :production do
  gem 'pg'
  gem 'rails_12factor'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
