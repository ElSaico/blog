source "https://rubygems.org"

gem "jekyll", "~> 4.0.0"
group :jekyll_plugins do
#  gem "github-pages", "~> 203"
  gem "jekyll-admin"
  gem "jekyll-include-cache"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
