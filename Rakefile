desc "Help"
task :help do
  puts <<HELP
All of these processes are taken by rake, below is the full list:

#{%x[bundle exec rake -T]}

HELP
end

task default: "help"
