source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"

group :jekyll_plugins do
    gem 'jekyll-scholar'
    gem 'jekyll-feed'
    gem 'jekyll-seo-tag'
end

gem "webrick"
gem "jekyll-swiss"