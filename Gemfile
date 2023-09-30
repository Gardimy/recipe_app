source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.2'

# Core gems
gem 'rails', '~> 7.0.7', '>= 7.0.7.2'
gem 'pg', '~> 1.1'
gem 'devise'

# Server and assets
gem 'puma', '~> 5.0'
gem 'sprockets-rails'
gem 'bootsnap', require: false

# JavaScript and frontend
gem 'importmap-rails'
gem 'turbo-rails'
gem 'stimulus-rails'
gem 'jbuilder'

# Database-related (if needed)
# Uncomment these lines if you are using these gems.
# gem 'redis', "~> 4.0"  # If you use Redis for caching or Action Cable
# gem 'kredis'           # If you use Kredis for Redis data types
# gem 'bcrypt', "~> 3.1.7" # If you use bcrypt for password hashing

# Other optional gems
# gem 'sassc-rails'      # If you use Sass for CSS
# gem 'image_processing', "~> 1.2" # If you use Active Storage variants

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'rails-controller-testing'
  gem 'letter_opener'
  gem 'web-console'
  # Uncomment the following line if you want to use rack-mini-profiler
  # gem "rack-mini-profiler"
  # Uncomment the following line if you want to use Spring for faster development
  # gem "spring"
end

group :test do
  gem 'capybara'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers'
  gem 'webdrivers'
end

# Windows-specific gem (keep this for cross-platform compatibility)
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
