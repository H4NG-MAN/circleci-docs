source 'https://rubygems.org'

ruby '2.6.3'

gem 'jekyll', '3.8.6'
gem 'html-proofer', '>= 3.14.1'
gem "rack", ">= 2.0.8"
gem 'asciidoctor'
gem 'asciidoctor-pdf', '~> 1.5.0.0.0'
gem 'pygments.rb', '~> 1.1.2'

group :jekyll_plugins do
  gem 'jekyll-algolia', '~> 1.6', '>= 1.6.0'
  gem 'jekyll-sitemap', '>= 1.3.1'
  gem 'jekyll-assets', '>= 3.0.12'
  # jekyll-assets depends on sprockets, which depends on rack, which has two
  # security vulnerabilities prior to 2.0.6.
  # https://nvd.nist.gov/vuln/detail/CVE-2018-16471
  # https://nvd.nist.gov/vuln/detail/CVE-2018-16470
  gem 'jekyll-asciidoc', '>= 2.1.1'
end
