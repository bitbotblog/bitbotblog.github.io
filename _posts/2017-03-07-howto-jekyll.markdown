---
layout: post
title:  "HowTo - Jeyll"
date:   2017-03-07 16:16:58 +0100
categories: jekyll update
---

How to configure Jekyll to use in [github pages][github-pages]

- Check out the tutorial from [GitHub-Jekyll][github-jekyll].
Here is everything neccesary to install jekyll in github pages,
and run a local server to see the changes before commit to git.


- If you have some problem to run the server, maybe it is neccesary to install node.js [See Could not find a JavaScript runtime][jsRuntime-node]

{% highlight bash %}
sudo apt-get install nodejs
{% endhighlight %}

- If you have problems with gem, see this error [Failed to build gem native extension][gem-nativeextension]

{% highlight bash %}
sudo apt-get install ruby-dev
{% endhighlight %}

- For wrtitting: [MarkDown Tutorial][markdown-tutorial]



[github-jekyll]: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
[github-pages]: https://pages.github.com/
[jsRuntime-node]: https://github.com/jekyll/jekyll/issues/2327
[gem-nativeextension]: https://github.com/jekyll/jekyll-help/issues/209
[markdown-tutorial]: http://www.markdowntutorial.com/
