# -*- encoding: utf-8; mode: ruby; tab-width: 2; indent-tabs-mode: nil -*-
source "https://rubygems.org"

gem "activerecord", :require => "active_record"
gem "foreigner"
gem "git"
gem "mercurial-ruby"
gem "rake"
gem "sinatra"
gem 'sinatra-contrib'
gem 'unicorn'

group :postgresql do
  gem "pg"
end

group :sqlite do
  gem "sqlite3"
end

group :mysql do
  gem "mysql2"
end

group :development do
  gem "racksh"
  gem "shotgun"
end