source 'https://rubygems.org'

gem 'curb'
gem 'redis'

## because fedora/rhel
install_if -> { RUBY_PLATFORM =~ /linux/ } do
  gem 'json'
end

group :test do
  gem 'rubocop', '~> 0.48.1', require: false
end
