require "rake"

task :build do
  sh "./bin/convert -f ./frontmatter.yml src/*.rb > uBlacklist.txt"
end

task :default => :build
