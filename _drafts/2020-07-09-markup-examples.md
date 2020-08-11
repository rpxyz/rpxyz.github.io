---
layout: post
title:  "Markup Examples"
date:   16-07-2020
permalink: /site/markup-examples/
published: false
---
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<b>Inline Image Snippet:</b>
{% highlight ruby %}
include inline-image.html src="welcome.png"
{% endhighlight %}

<b>Block Quote with a Title:</b>
{% highlight ruby %}
> A blockquote with a title
{:title="The blockquote title"}
{% endhighlight %}

<b>Instagram Embed:</b>
{% highlight ruby %}
<center>
<iframe src="https://www.instagram.com/p/B9UXu-WFmlQ/embed" width="400" height="480" frameborder="0" scrolling="no" allowtransparency="true"></iframe>
</center>
{% endhighlight %}

-> Change the "B9UXu-WFmlQ" for the image code on Instagram.

<b>YouTube Embed:</b>
{% highlight ruby %}
include embed-videos.html type='youtube' uid='prFohBWIdQg'
{% endhighlight %}

-> Change the "prFohBWIdQg" for the UID of Video.

<b>Table of Contents:</b>
{% highlight ruby %}
* TOC
{:toc}

## Test1
{% endhighlight %}