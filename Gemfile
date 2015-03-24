source 'https://rubygems.org'
ruby '2.2.0'

gem 'rails', '4.2.1'

group :development, :test do
# Use sqlite3 as the database for Active Record
	gem 'sqlite3'
	gem 'rspec-rails', '2.9.0'
# bundle exec rake doc:rails generates the API under doc/api.
	gem 'sdoc', '~> 0.4.0', group: :doc
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
	gem 'sass-rails', '~> 5.0'
# Use CoffeeScript for .coffee assets and views
  gem 'coffee-rails', '4.1.0'

# Use SCSS for stylesheets
# Use Uglifier as compressor for JavaScript assets
  gem 'uglifier'
end

gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

group :test do
	gem 'capybara', '1.1.2'
end

group :production do
	gem 'pg'
end
