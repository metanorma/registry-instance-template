source "https://rubygems.org"

# Replace YOUR-ORG topic org below via metanorma.aggregate.yml; bump via tagged releases
gem "metanorma-release", github: "metanorma/metanorma-release", tag: "v0.2.24"
# Registry engine: enrichment, schemas, validation and conformance harness.
# Bump via tagged engine releases.
gem "standards-registry", github: "metanorma/standards-registry", tag: "v1.0.1"
gem "octokit", "~> 9.0"
gem "rake", "~> 13.2"
# Add your Relaton flavor gem(s) here, e.g. relaton-iso

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "wdm", "~> 0.1.0" if Gem.win_platform?

group :test do
  gem "rspec", "~> 3.13"
  gem "json_schemer", "~> 2.0"
end
