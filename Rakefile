require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('tabula_recta', '0.1.0') do |p|
    p.description = "A gem for easily generating a tabula recta"
    p.url = "http://github.com/ehayon/tabula_recta"
    p.author = "Ethan Hayon"
    p.email = "ehayon@gmail.com"
    p.ignore_pattern = ["tmp/*", "script/*"]
    p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.eacg { |ext| load ext }