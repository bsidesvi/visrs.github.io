source "https://rubygems.org"

gem "jekyll-remote-theme"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-default-layout", "~> 0.1.4"
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-include-cache", "~> 0.2.0"
  gem 'github-pages', '~> 204'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

