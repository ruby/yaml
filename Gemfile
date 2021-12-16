source "https://rubygems.org"

group :development do
  gem "bundler"
  gem "rake"
  gem "test-unit"

  # Workaround for `unsafe_load`
  if "3.0" > RUBY_VERSION
    gem "psych", ">= 4.0"
  end
end
