# Rails Guide 中文翻译


## 构建

```bash
# linux or macOS
bundle install
RAILS_VERSION=v6.1.3 bundle exec rake guides:generate:html
```

```bash
# windows
bundle install
set RAILS_VERSION=v6.1.3 
bundle exec rake guides:generate:html
```

## 发布

另外 clone 一份 repo，checkout 到 `gh-pages` 分支，将 HTML 版内容拷贝进去，commit，push。
