source "https://rubygems.org"

gem "jekyll", "~> 4.4"
# gem "github-pages", group: :jekyll_plugins

gem "jekyll-sass-converter", "~> 3.1"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-file-size", "~> 0.0.7"
  gem "jekyll-node-module"
  gem "jekyll-redirect-from", "~> 0.16.0"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2", :install_if => Gem.win_platform?

gem "nokogiri", "~> 1.18"
gem "webrick", "~> 1.9"
