source 'http://rubygems.org'

#gem 'rails', '~> 3.2.8'
gem 'rails', github: 'rails/rails', branch: 'master'
gem 'journey', github: 'rails/journey'
gem 'activerecord-deprecated_finders', github: 'rails/activerecord-deprecated_finders'
gem 'protected_attributes', github: 'rails/protected_attributes'
gem 'acl9', '~> 0.12.0'
gem 'capistrano', '~> 2.8.0'
#gem 'devise', github: 'plataformatec/devise'
gem 'devise', github: 'parndt/devise', branch: 'rails4'
gem 'orm_adapter', github: 'ugisozols/orm_adapter', branch: 'rails4'
gem 'gravtastic', '~> 3.2.6'
gem 'haml', '~> 3.1.3'
gem 'paperclip', '~> 2.3'
gem 'uuid', '~> 2.3.1'
#gem 'jquery-rails', '~> 1.0.17'
gem 'rake', '~> 0.9.2'
gem 'state_machine', '~> 1.0.2'
gem 'googlecharts', '~> 1.6.8'
#gem 'github_concern', '~> 0.1'
gem 'github_concern', path: '/home/jadams/rails/github_concern'
#gem 'css3-progress-bar-rails', '~> 0.2.2'
gem 'grit', '~> 2.4.0'
#gem 'paper_trail', '~> 2.6.0'
gem 'paper_trail', github: 'parndt/paper_trail', branch: 'rails4'
gem 'attr_encrypted', '~> 1.2.0'
#gem 'acts-as-taggable-on', '~> 2.2.2'
gem 'acts-as-taggable-on', path: '/home/jadams/rails/acts-as-taggable-on'
gem 'acts_as_commentable', '~> 3.0.1'
gem 'dynamic_form', '~> 1.0.0'
gem 'kramdown'
#gem 'doorkeeper', '~> 0.4.2'
gem 'oauth2'
gem 'sidekiq', '2.0.3'

gem 'simple-navigation-bootstrap'
gem 'sass-rails', github: 'rails/sass-rails'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', github: 'rails/coffee-rails'
  gem 'uglifier', '>= 1.0.3'
  gem 'compass', '0.12.alpha.0'
  gem 'bootstrap-sass', '2.0.1'
end

group :development do
  gem 'awesome_print', '~> 0.4.0', :require => 'ap'
  gem 'rails_best_practices'
end

group :test do
  gem 'awesome_print', '~> 0.4.0',  :require => 'ap'
  gem 'capybara', '~> 1.1.1'
  gem 'cucumber', '~> 1.1.4'
  gem 'cucumber-rails', '~> 1.2.1', :require => false
  gem 'database_cleaner', github: "ugisozols/database_cleaner", branch: 'rails4'
  gem 'faker', '~> 0.9.5'
  gem 'forgery', '= 0.3.10'
  gem 'launchy', '~> 0.3.7'
  gem 'machinist', '~> 1.0.6'
  gem 'pickle', '= 0.4.8'
  gem 'shoulda-matchers', '~> 1.0'
  #gem 'simplecov', '~> 0.5.0'
  gem 'simplecov-rcov'
  gem 'spork', '0.9.0.rc9'
  gem 'ci_reporter'
end

platforms :jruby do
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'activerecord-jdbcmysql-adapter'
  gem 'jruby-openssl'
  gem 'trinidad'
end

platforms :ruby do
  gem 'pg'
  gem 'mysql2', '~> 0.3.0'
end

group :test, :development do
  # rspec-rails needs to be in the development group to expose generators
  # and rake tasks without having to type `RAILS_ENV=test`
  gem 'rspec-rails'
  gem 'pry-rails'
end

