source "https://rubygems.org"

ruby '3.4.2'

# gem "github-pages", ">= 228", group: :jekyll_plugins
gem "jekyll", "~> 4.3.2" # Use the latest version


# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.0"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# gem 'webrick', '>= 1.8.1', '< 2'
gem 'puma'

# Added for Ruby 3.4.0:
gem 'base64'
gem 'logger'
gem 'csv'

# Previously included by default.
gem 'jekyll-theme-slate'