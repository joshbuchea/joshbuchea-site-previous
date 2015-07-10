---
layout: post
title: Font Smoothing in Webkit and Firefox
---

If fonts on your website appear to be rendering "thicker" in Webkit or Firefox than they do in other applications (Photoshop, other browsers, etc.), the issue *may* be resolved by enabling font smoothing. Font smoothing can be enabled for Webkit & Firefox with the following CSS:

{% highlight css %}
body {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
{% endhighlight %}
