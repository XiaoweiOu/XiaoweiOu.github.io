source "https://rubygems.org"

gem "jekyll", "~> 4.3"

# Ruby 3 no longer bundles webrick, which `jekyll serve` needs
gem "webrick", "~> 1.8"

# Keep the libsass-based converter: the theme's 2020-era SCSS
# predates Dart Sass and would raise deprecation errors there
gem "jekyll-sass-converter", "~> 2.2"

# Official Plugins
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-seo-tag", "~> 2.8"
end
