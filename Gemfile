# frozen_string_literal: true

#source "https://rubygems.org"

#git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

#gem "jekyll", "~> 4.0"

#gem "jekyll-paginate"

#group :jekyll_plugins do
#   gem "jekyll-paginate"
#end

source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']