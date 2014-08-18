source 'http://rubygems.org'

gem 'maruku'
gem 'rake'
gem 'yard'

platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter'
  gem 'jdbc-sqlite3'
  gem 'jruby-openssl'
end

group :test do
  gem 'backports'
  gem 'minitest'
  gem 'rubocop', '>= 0.25'
  gem 'simplecov', '>= 0.9'
  gem 'sqlite3', :platforms => :ruby
  gem 'yardstick'
end

gemspec
