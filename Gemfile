source 'https://rubygems.org'
gemspec


unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'hanami-utils',       '~> 0.7', github: 'hanami/utils',       branch: '0.7.x'
gem 'hanami-validations', '~> 0.5', github: 'hanami/validations', branch: '0.5.x'
gem 'hanami-controller',  '~> 0.6', github: 'hanami/controller',  branch: '0.6.x'
gem 'hanami-view',        '~> 0.6', github: 'hanami/view',        branch: '0.6.x'

gem 'simplecov', require: false
gem 'coveralls', require: false
