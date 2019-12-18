source 'https://rubygems.org'
#The gemspec line tells bundler that it can find a .gemspec file alongside the Gemfile
#gemspec

#---------------------------------------------
# use local theme gem for testing
#gem "jekyll-theme-so-simple", path: "../"

#---------------------------------------------
# https://rubygems.org/gems/jekyll-theme-so-simple
gem 'jekyll-theme-so-simple', '~> 3.2'

#??
#gem "wdm", "~> 0.1.0" if Gem.win_platform?

#---------------------------------------------
## http://jekyllrb-ko.github.io/docs/github-pages/
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

#gem 'github-pages', versions['github-pages']

#gem 'github-pages'

#---------------------------------------------
#https://github.com/mmistakes/so-simple-theme#github-pages-method
gem "github-pages", group: :jekyll_plugins

#---------------------------------------------
#https://github.com/mmistakes/so-simple-theme#pagination
group :jekyll_plugins do
  gem "jekyll-paginate"
end
