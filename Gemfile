source "https://rubygems.org"

# GitHub Pages 호환 버전 사용
gem "github-pages", group: :jekyll_plugins

# 테마 (GitHub Pages 호환 버전)
gem "minima", "~> 2.5"

# 플러그인
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows 지원
platforms :windows do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0" if Gem.win_platform?