# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)
require 'rake'

SampleApp::Application.load_tasks
gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'

group :development do
  gem 'rspec-rails', '2.5.0'
end

group :test do
  gem 'rspec', '2.5.0'
  gem 'webrat', '0.7.1'
end
