# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.4'

# bcrypt() is a sophisticated and secure hash algorithm designed by The OpenBSD project
gem 'bcrypt', '~> 3.1', '>= 3.1.16'
# CoffeeScript adapter for the Rails asset pipeline
gem 'coffee-rails', '~> 5.0'
# High-level wrapper for processing images for the web with ImageMagick or libvips
gem 'image_processing', '~> 1.12', '>= 1.12.1'
# Simple mime type detection using magic numbers, filenames, and extensions
gem 'marcel', '~> 1.0', '>= 1.0.2'
# PG is the Ruby interface to the PostgreSQL RDBMS
gem 'pg', '~> 1.2', '>= 1.2.3'
# Puma is a simple, fast, threaded, and highly parallel HTTP 1.1 server for Ruby
gem 'puma', '~> 5.5', '>= 5.5.2'
# Ruby on Rails is a full-stack web framework optimized for programmer happiness
gem 'rails', '~> 6.1', '>= 6.1.4.1'
# A Ruby client that tries to match Redis' API one-to-one
gem 'redis', '~> 4.5', '>= 4.5.1'
# Sass adapter for the Rails asset pipeline
gem 'sass-rails', '~> 6.0'
# Shrine is a toolkit for file attachments in Ruby applications
gem 'shrine', '~> 3.4'
# Simple, efficient background processing for Ruby
gem 'sidekiq', '~> 6.3', '>= 6.3.1'
# Terser minifies JavaScript files by wrapping TerserJS to be accessible in Ruby
gem 'terser', '~> 1.1', '>= 1.1.8'

group :development, :test do
  # Byebug is a Ruby debugger
  gem 'byebug', '~> 11.1', '>= 11.1.3', platforms: %i[mri mingw x64_mingw]
  # RuboCop is a Ruby code style checking and code formatting tool
  gem 'rubocop', '~> 1.23', require: false
  # Automatic Rails code style checking tool
  gem 'rubocop-rails', '~> 2.12', '>= 2.12.4', require: false
end

group :development do
  # Annotates Rails/ActiveRecord Models, routes, fixtures, and others
  gem 'annotate', '~> 3.1', '>= 3.1.1'
  # Provides a better error page for Rails and other Rack apps
  gem 'better_errors', '~> 2.9', '>= 2.9.1'
  # Provides the Binding#of_caller method
  gem 'binding_of_caller', '~> 1.0'
  # The Listen gem listens to file modifications and notifies you about the changes
  gem 'listen', '~> 3.7'
end
