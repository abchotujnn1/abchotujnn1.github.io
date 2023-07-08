---
title:  "Linear regression"
mathjax: true
layout: post
categories: media
---

![Llinear Regression](https://cdn.analyticsvidhya.com/wp-content/uploads/2021/05/2.3.png)


## Introduction

The following are a set of methods intended for regression in which the target value is expected to be a linear combination of the features. In mathematical notation

## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

{% highlight %}

def add{a, b}:
    return a + b
    
{% endlighlight %}

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

<script src="https://gist.github.com/5555251.js?file=gist.md"></script>

## Images

{% include url="https://cdn.analyticsvidhya.com/wp-content/uploads/2021/05/2.3.png" %}

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}
