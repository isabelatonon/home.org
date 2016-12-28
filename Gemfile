source 'https://rubygems.org'

ruby '2.2.3'

gem 'rails', '4.2.4'
gem 'puma'
gem 'pg'

gem 'sass-rails', '~> 5.0'

gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'

gem 'devise'
gem "paperclip", "~> 4.3"

gem 'bootstrap-sass', '~> 3.2.0'
gem 'bootstrap-sass-extras'

gem "simple_form"
gem "font-awesome-rails"

gem 'disqus_rails'

gem 'delayed_job_active_record'
gem 'ckeditor'

group :production, :staging do
  gem 'rack-timeout'
  gem 'rails_12factor'
  gem 'newrelic_rpm'
  gem 'heroku-deflater'
  gem 'aws-sdk', '< 2.0'
end

group :development do
  gem 'rubycritic', :require => false
  gem 'better_errors'
  gem 'foreman'

  # Assets pipeline log messages
  gem 'quiet_assets'

  # Help to kill N+1 queries and unused eager loading
  gem 'bullet'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # Pry initializer
  gem 'pry-rails'

  # Ruby objects with style
  gem 'awesome_print'
  gem 'dotenv-rails'
  gem 'binding_of_caller'
end

group :test do
  gem 'simplecov', :require => false
  gem 'email_spec'
end
