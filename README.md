# diasy

A simple and noble theme based on [Noderce](https://github.com/willerce/hexo-theme-noderce) for hexo.

# demo
- [Demo](http://googleyixia.com/2014/04/19/a-simple-and-noble-theme-for-hexo/)

![hexo_theme_demo](http://googleyixia.com/img/2014/hexo_theme_demo.jpg)

## Install

```
git clone git@github.com:imbyron/hexo-theme-daisy.git themes/diasy
```

##Enable

Modify `theme` setting in `_config.yml` to `diasy`.

## Update

Execute the following command to update diasy.

```
cd themes/diasy
git pull
```

## Configuration
### 注意：一定要修改多说评论的`short_name`，否则评论模块不会生效（不改就都发到了我的多说后台-_-）。

```
menu:
  首页: /
  文章归档: /archives
  友情链接: /links
  关于: /about

excerpt_link: 阅读全文 >

google_analytics: UA-5353535-6

rss: /atom.xml

comment_provider: duoshuo
# Duoshuo comment
duoshuo:
  short_name: jiabin
```
