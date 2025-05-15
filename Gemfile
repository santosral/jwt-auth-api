source "https://rubygems.org"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 8.0.2"
# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"
# Use the Puma web server [https://github.com/puma/puma]
gem "puma", ">= 5.0"
# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Use the database-backed adapters for Rails.cache and Active Job
gem "solid_cache"
gem "solid_queue"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin Ajax possible
# gem "rack-cors"

# Use JWT for token-based authentication
gem "jwt", "~> 2.10"

# Structured and leveled logging with support for JSON output, log filtering, and external log services
gem "amazing_print", "~> 1.8"
gem "rails_semantic_logger", "~> 4.17"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false

  # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rails-omakase", require: false

  # Test framework [https://github.com/rspec/rspec-rails]
  gem "rspec-rails", "~> 8.0.0"

  # Fixtures replacement to easily create test data
  gem "factory_bot_rails", "~> 6.4"

  # Loads environment variables from .env file for local development
  gem "dotenv", "~> 3.1"

  # Used to generate fake but realistic test data (e.g., names, IPs, user agents)
  gem "faker", "~> 3.5"
end

group :development do
  gem "ruby-lsp-rspec", require: false
end
