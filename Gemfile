# Gemfile — works with GitHub Pages locally on Windows
source "https://rubygems.org"

# Pins Jekyll + official plugins to GitHub Pages versions
gem "github-pages", group: :jekyll_plugins

# Needed to serve locally on Ruby 3.x
gem "webrick", "~> 1.8"

# Windows-specific:# Gemfile — GitHub Pages compatible on Windows
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "webrick", "~> 1.8"

# Windows extras:
gem "tzinfo-data"   # <-- fixes "No source of timezone data could be found"
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

gem "tzinfo-data"   # <- Fixes "No source of timezone data could be found"
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]  # faster file watching
