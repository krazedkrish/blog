source 'https://rubygems.org'

ruby '2.3.0'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'org-ruby'
gem 'jekyll-sitemap'
gem 'pygments.rb'
