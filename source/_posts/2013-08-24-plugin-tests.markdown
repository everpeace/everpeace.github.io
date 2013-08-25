---
layout: post
title: "plugin tests"
date: 2013-08-24 15:35
comments: true
categories: 
---
This is a sample post for testing plugins.
<!-- more -->

# H1
## H2
### H3
* list
* list

1. nlist
2. nlist

### backtick code block
``` scala isBigGang.scala
def isBigGang(x: Int): (Boolean, String) =
         (x > 9, "Compared gang size to 9.")
```

### code block
{% codeblock isBigGang.scala lang:scala %} 
def isBigGang(x: Int): (Boolean, String) =
         (x > 9, "Compared gang size to 9.")
{% endcodeblock %}

### gist
{% gist 4964844 %}

### code include
{% include_code test.js %}

### jsFiddle
{% jsfiddle ccWP7 %}

### blockquote
{% blockquote @allanbranch https://twitter.com/allanbranch/status/90766146063712256 %}
Last night I lay in bed looking up at the stars in the sky and I thought to myself, where the heck is the ceiling.
{% endblockquote %}

### image
{% img http://placekitten.com/890/280 %}

### pull quotes
{% pullquote %}
Surround your paragraph with the pull quote tags. Then when you come to
the text you want to pull, {" surround it like this "} and that's all there is to it.
{% endpullquote %}

### video
{% video http://s3.imathis.com/video/zero-to-fancy-buttons.mp4 640 320 http://s3.imathis.com/video/zero-to-fancy-buttons.png %}