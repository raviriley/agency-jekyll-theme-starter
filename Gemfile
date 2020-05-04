source "https://rubygems.org"

#line 4 for gem-based theme, line 5 for remote theme.
#gem "jekyll-agency"
gem "jekyll-remote-theme"

# If you do not want to use GitHub Pages, comment out the line below, then run bundle update.
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", ">= 0.1.0" if Gem.win_platform?
