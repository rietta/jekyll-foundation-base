source 'https://www.rubygems.org'

# Rubinius should go faster and lighter than MRI
platforms :rbx do
  gem 'racc'
  gem 'rubysl'
end

gem 'jekyll'
gem 'jekyll-assets'
gem 'jekyll-asset-pipeline'
gem 'compass'
gem 'zurb-foundation'
gem 'yui-compressor'

# Slim
gem 'jekyll-slim', '~> 0.8.2'

# Server
gem 'rake'
gem 'puma'
gem 'rack-contrib'
gem 'rack-rewrite'

group :development  do
  gem 'guard-jekyll-plus', git: 'https://github.com/imathis/guard-jekyll-plus', branch: 'master'
  gem 'rb-fsevent'
  gem 'guard-livereload'
end