source 'http://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails'

# webserver
gem 'puma'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]

gem 'pg'
gem 'rails_12factor', '0.0.2'

#gem for apple push nots
gem 'houston'
gem 'pushmeup'

#gem for android push
# gem 'gcm'

#http requests
gem 'json'

#cross site reqs
gem 'rack-cors', :require => 'rack/cors'

#delayed jobs
# gem 'delayed_job_active_record'
gem 'resque', "~> 1.22.0"
gem 'redis'

#web design
gem 'bootstrap-sass', '3.2.0.0'
gem 'sass-rails',   '5.0.2'
gem 'uglifier',     '2.5.3'
gem 'coffee-rails', '4.1.0'
gem 'jquery-rails', '4.0.3'
gem 'turbolinks',   '2.3.0'

group :development, :test do
	gem 'rspec-rails'
	gem 'factory_girl_rails'
	#set ENV VAR
	gem 'dotenv-rails'
	gem 'byebug'
end

group :test do
	gem 'selenium-webdriver'
	gem 'capybara'
	gem 'guard-rspec'
  	gem 'launchy'
end
