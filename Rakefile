CC = "gcc"

require "rake/clean"
CLEAN << "*.o"

desc "Make binary program"
task "default" => "jyuunisi"

file "jyuunisi" => "jyuunisi.c" do |t|
  sh "#{CC} -o #{t.name} #{t.prerequisites[0]}"
end
