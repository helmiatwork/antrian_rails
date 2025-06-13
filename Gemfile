source "https://rubygems.org"

# --- Core Rails Setup ---
gem "rails", "~> 8.0.2"
gem "pg", "~> 1.5"
gem "puma", ">= 5.0"
gem "bootsnap", require: false
gem "tzinfo-data", platforms: %i[windows jruby]

# --- Caching, Queues, Websockets ---
gem "solid_cache"
gem "solid_cable"
gem "solid_queue"

# --- Deployment & Performance ---
gem "kamal", require: false
gem "thruster", require: false

# --- Authentication & Authorization ---
gem "devise", "~> 4.9"
gem "devise-jwt", "~> 0.12.1"
gem "devise_token_auth", "~> 1.2"
gem "omniauth", "~> 2.1"
gem "omniauth-rails_csrf_protection", "~> 1.0"

# --- API Support ---
gem "jsonapi.rb"
gem "rswag-api"
gem "rswag-ui"

# --- Background Jobs & Notifications ---
gem "fcm", "~> 2.0"
gem "mqtt", "~> 0.6.0"
gem "noticed", "~> 2.6"
gem "sidekiq", "~> 8.0"
gem "sidekiq-cron", "~> 2.2"

# --- Utilities ---
gem "aasm", "~> 5.5"
gem "dotenv-rails", "~> 3.1"
gem "email_validator", "~> 2.2"
gem "fasterer", "~> 0.11.0"
gem "ipaddress", "~> 0.8.3"
gem "phonelib", "~> 0.10.8"
gem "rotp", "~> 6.3"
gem "rqrcode", "~> 3.1"
gem "terbilang", "~> 0.0.6"
gem "to_bool", "~> 2.1"
gem "validates_timeliness", "~> 8.0"

# --- PDF Generation ---
gem "prawn", "~> 2.5"
gem "wicked_pdf", "~> 2.8"

# --- Security & Protection ---
gem "rack-attack", "~> 6.7"
gem "rack-cors", "~> 2.0"
gem "sentry-rails", "~> 5.25"
gem "sentry-ruby", "~> 5.23"

# --- Auditing ---
gem "paper_trail", "~> 16.0"

# --- Development & Test ---
group :development, :test do
  gem "brakeman", require: false
  gem "debug", platforms: %i[mri windows], require: "debug/prelude"
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "better_errors", "~> 2.10"
end

group :test do
  gem "capybara"
  gem "database_cleaner-active_record"
  gem "rspec-rails"
  gem "rswag-specs"
  gem "selenium-webdriver"
  gem "shoulda-matchers"
  gem "timecop"
  gem "vcr"
  gem "webdrivers"
  gem "webmock"
end

# --- Optional / Commented Out ---
# gem "bcrypt", "~> 3.1.7"
# gem "image_processing", "~> 1.2"
# gem "rack-cors"
