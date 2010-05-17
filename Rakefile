require 'rubygems'
require 'rake'

begin

  require 'jeweler'

  Jeweler::Tasks.new do |gem|

    gem.name        = 'dm-rails'
    gem.summary     = 'Use DataMapper with Rails 3'
    gem.description = 'Integrate DataMapper with Rails 3'
    gem.email       = 'gamsnjaga@gmail.com'
    gem.homepage    = 'http://github.com/datamapper/dm-rails'
    gem.authors     = [ 'Martin Gamsjaeger (snusnu)', 'Dan Kubb' ]

    gem.add_dependency 'dm-core',           '~> 0.10.2'
    gem.add_dependency 'dm-active_model',   '~> 0.4'

    gem.add_dependency 'activesupport',     '~> 3.0.0.beta3'
    gem.add_dependency 'actionpack',        '~> 3.0.0.beta3'
    gem.add_dependency 'railties',          '~> 3.0.0.beta3'
  end

  Jeweler::GemcutterTasks.new

  FileList['tasks/**/*.rake'].each { |task| import task }

rescue LoadError
  puts 'Jeweler (or a dependency) not available. Install it with: gem install jeweler'
end
