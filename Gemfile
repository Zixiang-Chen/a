# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"
gem "jekyll"
# https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/installation.md
gem 'jekyll-seo-tag'
gem 'jekyll-feed'
gem 'github-pages'

#Please add the following to your Gemfile to avoid polling for changes:
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

# https://github.com/MihajloNesic/jekyll-pdf-embed
group :jekyll_plugins do
  gem "jekyll-pdf-embed"
end

# https://jekyllrb.com/docs/step-by-step/01-setup/
# To create a new Gemfile to list your project’s dependencies run `bundle init`