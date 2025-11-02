source "https://rubygems.org"

# 核心 Jekyll
gem "jekyll", "~> 4.3.4"

# 常用插件
gem "jekyll-feed"
gem "jekyll-seo-tag"

# 修复 Ruby 3.4 缺失标准库问题
gem "webrick"   # 用于 serve，本地调试时必须
gem "logger"    # Ruby >= 3.4 需要手动声明
gem "csv"       # Ruby >= 3.4 需要手动声明
gem "base64"    # Netlify 官方推荐，防止依赖加载错误
