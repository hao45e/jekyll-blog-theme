# Jekyll博客模版
    我的博客日志记录模版

## 前端
* 响应式布局：Foundation
* 图标：FontAwesome
* 滚动条：mCustomScrollbar

## jekyll插件
* 订阅：jekyll-feed
* GitHub头像：jekyll-avatar
* 搜索站点地图：jekyll-sitemap
* 标题未指定时使用markdown标题：jekyll-titles-from-headings

## 使用教程
> 1. 已存在ruby环境,可以使用gem
```bash 
$ ruby -v 
$ gem -v
```
> 2. 安装jekyll使用到的jekyll插件
```bash
$ gem install bundler jekyll
$ gem install jekyll-feed jekyll-avatar jekyll-sitemap jekyll-titles-from-headings
```
> 3. fork到自己到代码库，克隆后进入项目并运行模版
```bash
$ git clone https://github.com/hao45e/blog.git
$ cd blog
$ jekyll serve
```
> 4. 将markdown的博客文件放入_posts目录下
> > layout 使用layouts目录下的某个的布局 <br>
> > title 标题 <br>
> > categories 分类 <br>
> > tag 标签 <br>