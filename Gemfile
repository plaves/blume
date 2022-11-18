source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails', '~> 7.0.4'
gem 'sqlite3', '~> 1.4'
gem 'puma', '~> 5.0'

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem 'kredis'

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem 'bcrypt', '~> 3.1.7'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'
gem 'jwt', '~> 2.5'
gem 'rodauth-rails', '~> 1.6'
gem 'active_model_serializers', '~> 0.10.13'

gem 'nanoid', '~> 2.0'
gem 'discard', '~> 1.2'
gem 'kaminari', '~> 1.2'
gem 'rack-cors', '~> 1.1'

group :development, :test do
  gem 'debug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'ffaker', '~> 2.21'
end

group :development do
  # gem 'listen', '~> 3.7'
  gem 'better_errors', '~> 2.9'
end

group :test do
  # gem 'shoulda', '~> 4.0'
  # gem 'factory_bot_rails', '~> 6.2'
end
