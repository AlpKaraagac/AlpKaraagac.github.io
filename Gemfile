# frozen_string_literal: true

source "https://rubygems.org"

# Let GitHub Pages manage Jekyll and dependencies
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jemoji"
  gem "jekyll-include-cache"
  gem "jekyll-algolia"
end

# Platform-specific gems for Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo"
  gem "tzinfo-data"
end

gem "wdm", platforms: [:mingw, :x64_mingw, :mswin]

# Required to run `jekyll serve` with Ruby 3+
gem "webrick"
