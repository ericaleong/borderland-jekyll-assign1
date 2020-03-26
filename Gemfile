source "https://rubygems.org"
git_source(:github) {|repo_name| 'https://github.com/#{repo_name}'}
gem 'github-pages'
gem "jekyll"
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

