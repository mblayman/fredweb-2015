# Frederick Web Tech - December 2015

*This repository contains the presentation
and demonstration material
used for the Frederick Web Tech event
in December 2015.*

## Exploring static site generators

How can you create websites
that are simple, beautiful, and extremely secure?
Use a static website generator.
We will explore the what, why, how, and where
of static site generators.
Come find out
if a site generator is just the tool you need.

Follow along by cloning
https://github.com/mblayman/fredweb-2015.git or
[check out the GitHub repo directly](https://github.com/mblayman/fredweb-2015).

## Jekyll

```bash
$ sudo apt-get install ruby-dev
$ gem install --user-install jekyll
$ ~/.gem/ruby/1.9.1/bin/jekyll new jekyll_demo
$ cd jekyll_demo
$ ~/.gem/ruby/1.9.1/bin/jekyll serve
```

## Hexo

```bash
$ sudo apt-get install npm
$ npm install hexo-cli
$ ./node_modules/hexo-cli/bin/hexo init hexo_demo
$ cd hexo_demo
$ ../node_modules/hexo-cli/bin/hexo generate
$ ../node_modules/hexo-cli/bin/hexo server
```

## Hugo

```bash
$ wget https://github.com/spf13/hugo/releases/download/v0.14/hugo_0.14_linux_amd64.tar.gz
$ tar xzf hugo_0.14_linux_amd64.tar.gz
$ ./hugo_0.14_linux_amd64/hugo_0.14_linux_amd64 new site hugo_demo
$ cd hugo_demo
$ ../hugo_0.14_linux_amd64/hugo_0.14_linux_amd64 new about.md
<add some Markdown to about.md>
$ git clone --recursive https://github.com/spf13/hugoThemes themes
$ ../hugo_0.14_linux_amd64/hugo_0.14_linux_amd64 server \
    --theme=hyde --buildDrafts --watch
```
