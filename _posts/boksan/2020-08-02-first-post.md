---
layout: post
title:  First Post
date:   2020-08-02 16:00:00 -0600
categories: jekyll
author: Boksan
published : true
permalink: /:categories/:year/:month/:day/:title
---

`YEAR-MONTH-DAY-title.MARKUP`

test post


{% highlight javascript %}
formatDate(date) {
  const options = { year: 'numeric', month: 'long', day: 'numeric' }
  return new Date(date).toLocaleDateString('en', options)
}
{% endhighlight %}