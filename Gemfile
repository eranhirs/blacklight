source 'https://rubygems.org'

# Please see blacklight.gemspec for dependency information.
gemspec


gem 'simplecov', require: false
gem 'coveralls', require: false

group :test do
  gem 'devise'
  gem 'devise-guests'
  gem "bootstrap-sass"
  gem 'turbolinks'
  gem 'sass-rails'
  gem 'blacklight-marc', :github => 'projectblacklight/blacklight_marc'
end

if File.exists?('spec/test_app_templates/Gemfile.extra')
  eval File.read('spec/test_app_templates/Gemfile.extra'), nil, 'spec/test_app_templates/Gemfile.extra'
end
