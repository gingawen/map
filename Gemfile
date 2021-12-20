source 'https://rubygems.org'

git_source(:github) do |test|
  test = "#{test}/#{test}" unless test.include?("/")
  "https://github.com/#{test}.git"
end

##gem 'rails', '~> 5.0.7.2'
gem 'puma', '~> 3.4.0'
gem 'sass-rails', '~> 6.0'
gem 'uglifier', '>= 2.7.2'
gem 'coffee-rails', '~> 5.2.0'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7.0'
gem 'railties', '~> 5.0.7.2'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'sqlite3'
end

group :production do
  gem 'pg'
end

group :development do
  gem 'web-console', '>= 3.7.0'
  gem 'listen', '~> 3.1.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]