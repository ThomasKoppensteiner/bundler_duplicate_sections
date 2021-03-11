# Bundler Duplicate Sections Issue MWE

This repository provides some minimum working examples for the
["Duplicate Sections in Gemfile.lock" issue](https://github.com/rubygems/rubygems/issues/4448).

Bundler version `2.2.14` duplicates the "GEM remote: https://rubygems.org/" section in the `Gemfile.lock`,
if it is specified twice in the `Gemfile`. This doesn't happen for Bundler version `2.2.13`.
