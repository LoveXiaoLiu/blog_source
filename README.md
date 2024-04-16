[![Build Status](https://app.travis-ci.com/LoveXiaoLiu/gra55_blog.svg?branch=master)](https://app.travis-ci.com/LoveXiaoLiu/gra55_blog)

# gra55_blog
Powered by [hugo](https://gohugo.io/commands/hugo/) and theme is [hugo-future-imperfect](https://github.com/jpescador/hugo-future-imperfect)

## Step
+ Install binary [hugo](https://github.com/gohugoio/hugo/releases)
+ Write new article，and article's picture from path (`.\static\img\`) that place by year and month
+ Go to the root path, and run `hugo.exe server` to preview
+ And then git push to github (will trigger [Travis-CI](https://www.travis-ci.org/), and then public to Github-Page. if it's not auto trigger, please check GitHub Token in Travis)

## PS
+ [icon](http://www.fontawesome.com.cn/)
+ ~~add `staticmanapp` to your Collaborators and access url `https://api.staticman.net/v2/connect/LoveXiaoLiu/blog-comment`~~
+ [add comment](https://www.yangliu.date//blog/2019/blog/hugo_plus_staticman/)
+ add [sina figure bed](https://photo.weibo.com/2322571331). You can use `img-post-fb` shortcodes, and use `figurebedurl` field in `.md` post file.
+ add `video-bili` shortcodes.
+ add `video-base` shortcodes, this is for html5 `video` tag, and now use for `miaopai`（just `F12` to get the video `src` url）.
