require "bundler/gem_tasks"

desc "Fetch new version from https://raw.github.com/angular-ui/ui-select2/master/src/select2.js"
task :fetch do
  source = "https://raw.github.com/angular-ui/ui-select2/master/src/select2.js"
  target = "vendor/assets/javascripts/angular-ui-select2-original.js"
  sh "curl #{source} > #{target}"
end
