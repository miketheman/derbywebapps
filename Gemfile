source 'https://rubygems.org'
ruby '2.6.1'

gem 'middleman', '~> 4.3', '>= 4.3.8'
gem 'middleman-livereload', '~> 3.4', '>= 3.4.6'

gem 'rack-contrib', '~> 2.2', '>= 2.2.0'
gem 'puma', '>= 4.3.5'

# For Markdown
gem 'redcarpet', '~> 3.5'

group :development do
  gem 'scss-lint', '>= 0.38.0'
end

# These gems are needed solely for generating other files,
# and are not part of the deployment bundle
group :codegen do
  gem 'bitters', '~> 1.0.0'
  gem 'bourbon', '4.2.6' # run `bourbon update --path ./source/css/`
  gem 'neat', '~> 1.7.1' # TODO: bump when https://github.com/thoughtbot/neat/pull/294 released.
end
