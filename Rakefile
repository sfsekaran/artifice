require "rubygems"
require "bundler"
Bundler.setup

task :spec do
  system "spec -cfs spec"
end

task :gem do
  system "bundle exec gem build artifice.gemspec"
end

task :default => :spec