source "https://rubygems.org"

# github-pages
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
    gem "jekyll-remote-theme"
    gem "jekyll-feed"
    gem "jekyll-seo-tag"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", ">= 1", "< 3"
    gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]