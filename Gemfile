source "https://rubygems.org"

# Upgrade Jekyll and essential Liquid rendering gems
gem "jekyll", "~> 4.3"
# gem "liquid", "~> 5.5"

# Group for plugins to avoid loading errors in production
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-sitemap", "~> 1.4"
  # If hosting on GitHub Pages, use the modern plugin wrapper instead of the monolithic gem:
  # gem "github-pages", "~> 232", group: :jekyll_plugins
end

# Required Ruby standard library gems split in Ruby 3.4+
gem "csv"
gem "base64"
gem "bigdecimal"
gem "mutex_m"
gem "webrick" # Required for local serving in modern Ruby