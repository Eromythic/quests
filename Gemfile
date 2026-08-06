source "https://rubygems.org"

# Jekyll 4 — built and deployed via GitHub Actions (see .github/workflows/jekyll.yml).
# The classic GitHub Pages branch build only supports Jekyll 3, so don't switch back
# to the github-pages gem unless also reverting the Pages source to "Deploy from a branch".
gem "jekyll", "~> 4.4"

# Windows and JRuby do not include zoneinfo files, so bundle tzinfo-data.
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows.
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb to v0.6.x on JRuby (no newer Java counterpart).
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
