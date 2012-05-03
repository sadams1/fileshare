source 'http://rubygems.org'

#for local and heroku development
group :development, :test do
  gem 'ruby-mysql'
end
group :production do
  gem 'pg'
end

gem 'rails', '3.0.3'
#gem 'ruby-mysql'

#for user authentication
gem 'devise'

#for layout and helpers generations
gem "nifty-generators", :group => :development

#for uploading files
gem "paperclip", "~> 2.3"
gem "mocha", :group => :test

#for Paperclip to use Amazon S3
gem "aws-sdk"

#for nested folders
gem "acts_as_tree"

#for preventing CSRF attacks
gem "jquery-rails"

#for heroku postgre
gem "postgres-pr"

#for help with db and pg
gem "taps"
