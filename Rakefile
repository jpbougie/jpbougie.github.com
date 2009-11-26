task :build do
  sh "jekyll"
end

task :deploy => :build do
  sh "rsync -rtz --delete _site/ jpbougie:/data/jpbougie.net"
end