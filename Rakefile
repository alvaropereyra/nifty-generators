require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('xenda-nifty-generators', '0.3.2') do |p|
  p.project        = "niftygenerators"
  p.description    = "A collection of useful generator scripts for Rails with extra juice"
  p.url            = "http://github.com/xenda/nifty-generators"
  p.author         = 'Alvaro Pereyra'
  p.email          = "alvaro (at) xendacentral (dot) com"
  p.ignore_pattern = ["script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
