# Load DSL and set up stages
require 'capistrano/setup'

# Include default deployment tasks
require 'capistrano/deploy'

require 'capistrano/scm/git'
install_plugin Capistrano::SCM::Git

require 'capistrano/rails'
require 'capistrano/rbenv'
require 'capistrano/passenger'

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }
set :rbenv_type, :user
set :rbenv_ruby, '3.0.0'

# Sidekiq lifecycle tasks
after 'deploy:starting', 'sidekiq:quiet'
after 'deploy:updated', 'sidekiq:stop'
after 'deploy:published', 'sidekiq:start'
after 'deploy:failed', 'sidekiq:restart'

