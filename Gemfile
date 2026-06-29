source "https://rubygems.org"

# Use the github-pages gem so the local build matches GitHub Pages' build exactly.
gem "github-pages", group: :jekyll_plugins

# Windows and JRuby do not include zoneinfo files, so bundle tzinfo-data.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows.
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb to v0.6.x on JRuby (no newer Java counterpart).
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
