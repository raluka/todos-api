require 'capistrano/setup'
require 'capistrano/deploy'
require 'capistrano/bundler'
require 'rollbar/capistrano3'
require 'capistrano/rails/migrations'
require 'capistrano/scm/git'
install_plugin Capistrano::SCM::Git

# Load custom tasks from `lib/capistrano/tasks' if you have any defined
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }

require 'tasks/deploy'
