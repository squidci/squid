require 'sinatra/activerecord/rake'
require_relative 'lib/api'

require 'rspec/core/rake_task'

task :default => [:spec]

desc 'Run specs'
RSpec::Core::RakeTask.new do |t|
  t.pattern = 'spec/**/*_spec.rb'
end
