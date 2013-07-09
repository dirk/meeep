require 'grancher/task'


class Grancher::Task
  include Rake::DSL
end

Grancher::Task.new do |g|
  g.branch = 'gh-pages'
  g.push_to = 'github'
  g.repo = 'meeep'
  g.message = 'Update'
  g.directory 'output'
end
