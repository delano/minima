# frozen_string_literal: true

source "https://rubygems.org"

# Temp fix for build error:
# sass-embedded-1.62.0-x86_64-linux-musl requires rubygems version >= 3.3.22
gem "rubygems-update", ">= 3.3.22", "< 4.0"

gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
