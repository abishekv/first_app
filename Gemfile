source 'https://rubygems.org'

gem 'rails', '3.2.13'




# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'

  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails'

group :production, :staging do
  gem "pg"
end

group :development, :test do
  gem "sqlite3", "~> 1.3.6", :require => "sqlite3"
end