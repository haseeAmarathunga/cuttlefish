# frozen_string_literal: true

source "https://rubygems.org"

gem "dotenv-rails", ">= 2.5.0"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem "rails", "5.2.0"

gem "pg"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem "sass-rails", ">= 5.0.7"
  # Don't upgrade to Bootstrap 3. It's already responsive, for example, so
  # there's a bunch of things we need to do for the upgrade
  gem "bootstrap-sass", "~> 2.0"

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem "therubyracer", platforms: :ruby

  gem "less-rails", ">= 3.0.0"
  gem "uglifier"
end

gem "jquery-rails", ">= 4.3.3"

gem "jbuilder"

gem "eventmachine"
gem "sidekiq"
gem "sinatra", require: nil

gem "batch-loader"
gem "devise", ">= 4.4.3"
gem "devise_invitable", ">= 1.7.4"
gem "dkim"
gem "dnsbl-client"
gem "factory_bot_rails", ">= 4.10.0"
gem "file-tail"
gem "foreman"
gem "formtastic", ">= 2.3.1"
# Use pull request that has needed Rails 4 improvements https://github.com/pkurek/flatui-rails/pull/25
gem "flatui-rails", git: "https://github.com/iffyuva/flatui-rails.git",
                    ref: "3d3c423"
gem "fog-aws", ">= 3.0.0"
gem "font-awesome-rails", ">= 4.7.0.4"
gem "friendly_id"
gem "google-analytics-rails"
gem "graphql"
gem "graphql-client"
gem "graphql-guard"
gem "gravatar_image_tag"
gem "haml-rails", ">= 1.0.0"
gem "honeybadger"
gem "syslog_protocol"
gem "will_paginate"
# Need commit c9331088146e456a69bd6e94298c80d09be3ee74
gem "formtastic-bootstrap",
    git: "https://github.com/mjbellantoni/formtastic-bootstrap.git",
    ref: "f86eaef93bea0a06879b3977d7554864964a623f"
gem "haml-coderay"
gem "minitar"
gem "newrelic_rpm"
gem "nokogiri", ">= 1.10.5"
gem "premailer"
gem "pundit"
gem "user_agent_parser"
gem "virtus"

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', group: :development

# To use debugger
# gem 'debugger'

group :development do
  gem "capistrano", "~> 2"
  gem "faker", git: "https://github.com/stympy/faker.git", branch: "master"
  gem "graphiql-rails", ">= 1.4.10"
  gem "guard"
  gem "guard-rspec"
  gem "listen"
  gem "rack-mini-profiler"
  gem "rb-fchange", require: false
  gem "rb-fsevent", require: false
  gem "rb-inotify", require: false
  gem "rubocop", require: false
  gem "rvm-capistrano", ">= 1.5.6", require: false
  gem "spring"
  gem "spring-commands-rspec"
  gem "terminal-notifier"
  gem "terminal-notifier-guard"
  # Webrick gives us annoying warnings "could not determine content-length
  # of response body"
  gem "thin"
end

group :test do
  gem "climate_control"
  gem "coveralls", require: false
  gem "database_cleaner"
  gem "rails-controller-testing", ">= 1.0.2"
  gem "vcr"
  gem "webmock"
end

group :development, :test do
  gem "capybara", ">= 3.3.1"
  gem "rspec-activemodel-mocks"
  gem "rspec-rails", ">= 3.7.2"
  gem "selenium-webdriver"
  # For resizing screenshots
  gem "rmagick"
end
