# source "https://rubygems.org"

# # Hello! This is where you manage which Jekyll version is used to run.
# # When you want to use a different version, change it below, save the
# # file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
# #
# #     bundle exec jekyll serve
# #
# # This will help ensure the proper Jekyll version is running.
# # Happy Jekylling!

# gem "github-pages", group: :jekyll_plugins

# # If you want to use Jekyll native, uncomment the line below.
# # To upgrade, run `bundle update`.

# # gem "jekyll"

# gem "wdm", "~> 0.1.0" if Gem.win_platform?

# # If you have any plugins, put them here!
# group :jekyll_plugins do
#   # gem "jekyll-archives"
#   gem "jekyll-feed"
#   gem 'jekyll-sitemap'
#   gem 'hawkins'
# end


source "https://rubygems.org"

# Use native Jekyll (modern) for local dev
gem "jekyll", "~> 4.3"

# Common plugins used by the template
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-paginate"
  gem "jekyll-remote-theme"
  gem "jemoji"
  gem "jekyll-gist"           # 你刚才缺少的
  gem "jekyll-redirect-from"  # 这次报错的主角
  gem "jekyll-github-metadata" # 若 _config.yml 有用 site.github，就需要
  gem "faraday-retry"         # 消除 “To use retry middleware…” 的提示
end
# Ensure precompiled Nokogiri on Linux, avoid building from source
gem "nokogiri", ">= 1.15.5"