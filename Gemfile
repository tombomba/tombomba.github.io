source "https://rubygems.org"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages'], group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-sitemap", "~> 1.2"
  gem "jekyll-feed", "~> 0.6"
end
