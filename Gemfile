# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

#gem "therubyracer"
gem "middleman", "~>3.1.4"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"
gem 'middleman-gh-pages'
# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]
gem "github-markup"
gem "redcarpet"
gem "sinatra"
gem 'sinatra-contrib'
gem "pry"

gemspec

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end