source 'https://rubygems.org'

# Distribute your app as a gem
gemspec

# Server requirements
# gem 'thin' # or mongrel
# gem 'trinidad', :platform => 'jruby'

# Optional JSON codec (faster performance)
# gem 'oj'

# Project requirements
gem 'rake'
gem 'dotenv'

# Component requirements
gem 'activerecord-jdbcpostgresql-adapter'
gem 'sequel'
gem 'slim'

# Test requirements
gem 'rspec', :group => 'test'
gem 'rack-test', :require => 'rack/test', :group => 'test'

# Padrino Stable Gem
gem 'padrino', '0.12.4'

# Auth
gem 'omniauth-twitter'
gem 'warden'

# Buffy
gem 'twitter'

# JRuby requirements

gem 'jruby-openssl', '~> 0.9.6'
gem 'jruby-rack'
gem 'warbler'

# Or Padrino Edge
# gem 'padrino', :github => 'padrino/padrino-framework'

# Or Individual Gems
# %w(core support gen helpers cache mailer admin).each do |g|
#   gem 'padrino-' + g, '0.12.4'
# end

group :development do
  gem 'pry'
end

group :test do
  gem 'generative'
  gem 'degenerate'
end
