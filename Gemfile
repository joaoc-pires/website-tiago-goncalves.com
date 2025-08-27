source "https://rubygems.org"

# GitHub Pages bundle (pins Jekyll + approved plugins)
gem "github-pages", group: :jekyll_plugins

# Needed locally on Ruby 3+ for `jekyll serve`
gem "webrick", "~> 1.8"

# Windows-only extras (ignored on macOS/Linux)
platforms :windows do
  gem "wdm", "~> 0.1.1"
  gem "tzinfo-data"
end

group :jekyll_plugins do
  gem "jekyll-sitemap"    # already included by github-pages; harmless duplicate
  # gem "jekyll-paginate" # only if your _config.yml uses it (Pages includes it)
  # gem "hawkins"         # REMOVE: not supported by GitHub Pages
end