# Jekyll 最小化站点（Minima）

这是一个基于 `Jekyll` + `minima` 主题的最小化静态站点

## 当前目录结构

- `_config.yml`：站点配置（标题、`baseurl`、主题、导航等）
- `Gemfile` / `Gemfile.lock`：Ruby 依赖（Jekyll、minima、插件）
- `index.md`：首页（`layout: page`）
- `about.md`：关于页面（`layout: page`，固定链接 `/about/`）

## 本地运行

1. 安装 Ruby（Windows 可用 RubyInstaller）
2. 在项目根目录执行：
   - `bundle install`
   - `bundle exec jekyll serve --livereload`

说明：
- 你当前配置了 `baseurl: "/chuzihang"`，本地通常访问 `http://127.0.0.1:4000/chuzihang/`
- 如果希望本地从根路径访问，可用：`bundle exec jekyll serve --baseurl ""`


