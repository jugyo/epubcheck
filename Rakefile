require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "epubcheck"
    gem.summary = %Q{command-line ePub check tool}
    gem.description = %Q{This is a command-line ePub check tool. It is wrapper of epubcheck(https://github.com/w3c/epubcheck).}
    gem.executables = ["epubcheck"]
    gem.files = Dir['lib/**/*']
    gem.email = "jugyo.org@gmail.com"
    gem.homepage = "http://github.com/jugyo/epubcheck"
    gem.authors = ["jugyo"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end
