#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

Locomotive::Application.load_tasks

namespace :doc do
  YARD::Rake::YardocTask.new(:app) do |t|
    t.files += ['app/**/*.rb']
    t.files += ['lib/**/*.rb']
  end
end
