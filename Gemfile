source "http://rubygems.org"

gem 'firering', :github => 'icco/firering', :branch => 'fix_logging_bug'

# Specify your gem's dependencies in camper_van.gemspec
gemspec

# specified here rather than in gemspec because they're
# for local mac development only
group :development do
  gem "rb-fsevent", :require => false
  gem "guard-minitest"
end
