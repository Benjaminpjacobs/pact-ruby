source 'https://rubygems.org'

# Specify your gem's dependencies in pact.gemspec
gemspec

if ENV['X_PACT_DEVELOPMENT']
  gem "pact-support", path: '../pact-support'
  gem "pact-mock_service", path: '../pact-mock_service'
  gem "pry-byebug"
end

group :local_development do
  gem "pry-byebug"
end
