# If you do not have OpenSSL installed, update
# the following line to use "http://" instead
source 'https://rubygems.org'

gem "middleman", "~> 3.4.0"
gem "middleman-syntax"
gem "redcarpet" # For github-flavored markdown
gem "middleman-navtree"
gem "titleize", "~> 1.3.0" # For title-casing things

# For faster file watcher updates on Windows:
gem "wdm", "~> 0.1.0", :platforms => [:mswin, :mingw]

group :development do
  gem "middleman-livereload", "~> 3.1.0"
  gem "pry"
end

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end
