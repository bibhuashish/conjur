source 'https://rubygems.org'

#ruby=ruby-2.2.4
#ruby-gemset=possum

gem 'rake'
gem 'rails-api'
gem 'rails', '~> 4.2'
gem 'puma'
gem 'sequel'
gem 'pg'
gem 'sequel-rails', github: 'dividedmind/sequel-rails', tag: '12-factor'
gem 'base32-crockford'
gem 'activesupport'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'random_password_generator', '= 1.0.0'
gem 'slosilo', '>=2.0.0'
gem 'listen'
gem 'gli'

gem 'rack-rewrite'
gem 'conjur-rack', github: 'conjurinc/conjur-rack', branch: 'master'
gem 'conjur-rack-heartbeat'
gem 'conjur-policy-parser', github: 'conjurinc/conjur-policy-parser', branch: 'master'

group :development, :production do
  gem 'rails_stdout_logging'
end

group :development, :test do
  gem 'spring'
  gem 'spring-commands-cucumber'
  gem 'spring-commands-rspec'
  gem 'json_spec'
  gem 'conjur-cli'
  gem 'conjur-debify'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'ci_reporter_rspec'
  gem 'parallel'
  gem 'cucumber'
  gem 'aruba'
  gem 'byebug'
  gem 'rake_shared_context'
end
