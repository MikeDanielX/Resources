source "https://rubygems.org"

# Specify the Jekyll version. ~> 4.0 means 4.x.x, but not 5.0
gem "jekyll", "~> 4.3"

# Essential for 'jekyll serve' on Ruby 3.0+ (Windows often needs this)
gem "webrick"

# List your plugins here, inside a group for Jekyll to pick them up
group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-toc"
  # You had '- jekyll-search' in _config.yml, but this is not a standard gem.
  # If it refers to a custom local plugin, you'll need to handle it differently.
  # For now, we'll omit it until your core setup works.
  gem "minima", "~> 2.5" # Or "~> 3.0" if you want the newer Minima version
end