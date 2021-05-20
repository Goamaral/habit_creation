source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'

# Must be the first gem
gem 'dotenv-rails', '~> 2.7', '>= 2.7.6', require: 'dotenv/rails-now', groups: [:development]

# RAILS #
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.3'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'tzinfo-data', '~> 1.2020', '>= 1.2020.4'

# GENERAL #
gem 'grape', '~> 1.5', '>= 1.5.1'

group :development do
  # RAILS #
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  # GENERAL #
  gem 'byebug', '~> 11.1', '>= 11.1.3'
end