source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.3'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Jb is a faster alternative to jbuilder"
gem 'jb', '~> 0.8'
# A fast JSON parser and Object marshaller
gem 'oj', '~> 3.11'
# An attempt to tame noisy Rails logs
gem "lograge"
# Minimal and simple authorization through OO
gem 'pundit', '~> 2.1'
# Flexible authentication solution for Rails with Warden
gem 'devise', '~> 4.7'

# A Rails engine for static pages
gem 'high_voltage', '~> 3.1'
# Hotwire is an alternative approach to building modern web applications
gem 'hotwire-rails'
# Add javascript sprinkles to your views
gem 'stimulus-rails'
# Tailwind CSS for Rails
gem 'tailwindcss-rails'
# Embedded SVGs for easy styling
gem 'inline_svg'

# Simple, efficient background processing alternative to ActiveJob
gem 'sidekiq', '~> 6.1'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # A convenient way to manage environment variables
  gem 'dotenv-rails'
  gem 'rubocop', '~> 1.10', require: false
  gem "rspec-rails"
  gem "factory_bot_rails"
end

group :development do
  # Add a comment summarizing the current schema to  your code
  gem 'annotate', '~> 3.1'
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  # Capistrano is used to deploy your application
  gem "capistrano", "~> 3.15", require: false
  gem "capistrano-rails", "~> 1.6", require: false
  gem 'capistrano-passenger', '~> 0.2.0', require: false
  gem 'capistrano-rbenv', '~> 2.2', '>= 2.1.4', require: false
end

group :test do
  gem "shoulda-matchers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
