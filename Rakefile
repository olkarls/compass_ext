require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "compass_ext"
    gem.summary = %Q{My frequently used mixins.}
    gem.description = %Q{}
    gem.email = "olkarls@gmail.com"
    gem.homepage = "http://github.com/olkarls/compass_ext"
    gem.authors = ["Ola Karlsson"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end

require 'rake/rdoctask'
Rake::RDocTask.new do |rdoc|
  version = File.exist?('VERSION') ? File.read('VERSION') : ""

  rdoc.rdoc_dir = 'rdoc'
  rdoc.title = "the-perfect-gem #{version}"
  rdoc.rdoc_files.include('README*')
  rdoc.rdoc_files.include('lib/**/*.rb')
end
