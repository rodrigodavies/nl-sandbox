source 'https://rubygems.org'

ruby '2.1.5'

gem 'rails', '~> 4.2.0'
gem 'nokogiri', '1.6.5'
gem 'thin'

# Make heroku serve static assets and loggin with stdout
gem 'rails_12factor'

# Assets
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'neighborly-style', github: 'neighborly/style', branch: :master
gem 'sass-rails'
gem 'autoprefixer-rails'
gem 'uglifier'
gem 'slim-rails'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'sqlite3'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

group :production do
  gem 'pg'
end