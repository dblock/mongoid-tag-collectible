source 'http://rubygems.org'

gemspec

case version = ENV['MONGOID_VERSION'] || '~> 4.0'
when /4/
  gem 'mongoid', '~> 4.0'
when /3/
  gem 'mongoid', '~> 3.1'
else
  gem 'mongoid', version
end

gem 'rspec'
gem 'rake'
gem 'rubocop', '0.32.1'
