# frozen_string_literal: true
source "https://rubygems.org"
ruby "2.4.0"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "babel-transpiler"
gem "bootstrap", github: "twbs/bootstrap-rubygem"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "pg", "~> 0.18"
gem "puma", "~> 3.7"
gem "rails", "5.0.3"
gem "sass-rails", github: "rails/sass-rails", branch: :master
gem "sprockets", github: "rails/sprockets", branch: :master
gem "sprockets-rails", github: "rails/sprockets-rails", branch: :master
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "capybara"
  gem "jazz_fingers"
  gem "poltergeist"
  gem "rspec-rails", "~> 3.5"
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "pry-rails"
  gem "spring"
  gem "spring-commands-rspec"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]