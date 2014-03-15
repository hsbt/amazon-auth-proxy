# -*- coding: utf-8 -*-

require 'rake'

if ENV['RACK_ENV'] != 'production'
  require 'rspec/core/rake_task'

  desc 'Run the code in spec'
  RSpec::Core::RakeTask.new(:spec) do |t|
    t.pattern = "spec/*_spec.rb"
  end
end
