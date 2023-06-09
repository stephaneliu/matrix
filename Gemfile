# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.1'

gem 'rails', '~> 7.0.4', '>= 7.0.4.3'

# Default
gem 'bootsnap', require: false # Reduces boot times through caching; required in config/boot.rb
gem 'jbuilder'                 # Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem 'pg', '~> 1.1'             # Use postgresql as the database for Active Record
gem 'puma', '~> 5.0'           # Use the Puma web server [https://github.com/puma/puma]
gem 'redis', '~> 4.0'          # Use Redis adapter to run Action Cable in production
gem 'sprockets-rails'          # The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem 'stimulus-rails'           # Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem 'turbo-rails'              # Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]

# Asset management
gem 'vite_rails' # Frontend tooling [https://github.com/ElMassimo/vite_ruby]

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw] # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
end

group :development do
  gem "solargraph-rails", "0.3.0"
  gem 'web-console' # Use console on exceptions pages [https://github.com/rails/web-console]
  # gem "rack-mini-profiler" # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
end

# gem "kredis"                     # Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "bcrypt", "~> 3.1.7"         # Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "sassc-rails"                # Use Sass to process CSS
# gem "image_processing", "~> 1.2" # Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
