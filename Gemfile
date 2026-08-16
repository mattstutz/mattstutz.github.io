source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.4.1"
# This is the default theme for new Jekyll sites. You may change this to anything you like.

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Minimal Mistakes Theme
gem "minimal-mistakes-jekyll"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-include-cache"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-paginate"
end

# Essenziell für Ruby 3.x auf Linux-Servern
gem "webrick", "~> 1.8"
gem "bigdecimal", "~> 3.1"
gem "mutex_m", "~> 0.2"

# Verhindert SassC-Kompilierungsfehler auf Ubuntu
gem "sassc-embedded", "~> 1.78"

gem "faraday-retry"