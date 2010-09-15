require 'jeweler'

task :default => :build

Jeweler::Tasks.new do |s|
  s.name = 'fluther'
  s.summary = 'Ruby interface to the Fluther discussion system'
  s.email = 'steve@conceivian.com'
  s.homepage = 'http://github.com/conceivian/fluther'
  s.description = 'Ruby interface to the Fluther discussion system'
  s.authors = ['Steve Sloan', 'Justin Chen']
  s.files = FileList[ 
     'MIT-LICENSE',
     'README.textile',
      'lib/**/*'
  ]
  s.add_dependency 'em-http-request'
end
Jeweler::GemcutterTasks.new
