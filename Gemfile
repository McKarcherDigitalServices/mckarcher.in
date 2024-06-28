source "https://rubygems.org"

ruby "3.1.1"

gem "jekyll", "~> 4.1.1"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-archives"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
gem "webrick", "~> 1.8"

# Remove the version constraint for public_suffix
gem "public_suffix"
