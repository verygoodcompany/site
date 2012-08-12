source 'https://rubygems.org'

gem 'thin'

gem 'eventmachine', '1.0.0.beta.4'
gem 'sinatra'
gem 'sinatra-contrib', :require => 'sinatra/contrib'
gem 'sinatra-flash', :require => 'sinatra/flash'

gem 'rack-protection'

gem 'slim'

gem 'pg'
gem 'datamapper'
%w(core postgres-adapter validations timestamps migrations constraints aggregates types pager is-tree).each do |g|
  gem 'dm-' + g
end
gem 'bcrypt-ruby', :require => "bcrypt"

group :development do
  gem 'pry'
  gem 'dm-sqlite-adapter'
end

gem 'omniauth-identity', :git => 'git://github.com/intridea/omniauth-identity.git'