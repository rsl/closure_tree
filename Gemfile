source 'https://rubygems.org'

platforms :ruby, :rbx do
  gem 'mysql2'
  gem 'pg', '~> 0.21'
  gem 'sqlite3'
end

platforms :jruby do
  gem 'activerecord-jdbcmysql-adapter'
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'activerecord-jdbcsqlite3-adapter'
end

gemspec
