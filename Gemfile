# frozen_string_literal: true

source "https://rubygems.org"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem 'github-pages', group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-avatar"
  # https://stackoverflow.com/questions/72878952/bundle-exec-jekyll-build-wrong-number-of-arguments-given-2-expected-1-argum
  gem "jekyll-assets", git: "https://github.com/envygeeks/jekyll-assets", ref: "refs/pull/666/head"
  gem "jekyll-remote-theme"
  gem "jekyll-paginate"
  gem "jekyll-default-layout"
  gem "jekyll-relative-links"
  gem "jekyll-github-metadata"
  gem "jekyll-mentions"
  gem "jekyll-gist"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jemoji"
end

group :development, :test do
  gem 'dotenv-rails'
end

gemspec

# https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll
gem "webrick", "~> 1.8"
gem "github-pages", "~> 228"
# https://stackoverflow.com/questions/72878952/bundle-exec-jekyll-build-wrong-number-of-arguments-given-2-expected-1-argum
gem "jekyll", "~>3.9"
gem "sprockets"
# https://stackoverflow.com/questions/62720043/rails-why-is-bundle-install-frozen-up-by-sassc-2-4-0
gem 'sassc', '~> 2.1.0'
