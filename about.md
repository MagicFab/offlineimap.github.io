---
layout: page
title: About
permalink: /about/
---

This is the OfflineIMAP community's website. It is made *open*, *static* and *easy*.

You can expect maintainers and users to blog here about OfflineIMAP.

The website engine is [Jekyll][jekyll] which relies on *[kramdown syntax][kramdown]*, derivated from the well-known markdown.  The source of this page (`about.md`) is a good sample of the basics of the syntax. See how it's easy to contribute to the site by yourself.

You are welcome to propose updates or write your own blog post. ,-)


## Updating the website

If you already have a copy of the `offlineimap` repository, get into it and run:

{% highlight bash %}
$ ./clone-website.sh
{% endhighlight %}

Otherwise, it's possible to clone the this website directly:

{% highlight bash %}
$ git clone https://github.com/OfflineIMAP/website.git
{% endhighlight %}

Make your changes and sumbit them to the maintainers, as for usual patches.


## About Jekyll

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. Bug and feature requests for Jekyll are at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

### The theme


The look is very important. Feel free to add your own touch! We started from the base Jekyll theme because it's clean and simple.

You can get inspiration from other's customized themes.


## Other ressources

* <http://jekyllrb.com/docs/structure/>
* <https://help.github.com/articles/repository-metadata-on-github-pages/>
* <https://gist.github.com/jedschneider/2890453>
* <https://help.github.com/articles/using-jekyll-with-pages/#configuring-jekyll>
* <http://ben.balter.com/2014/03/13/pages-anchor-links/>


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[kramdown]:    http://kramdown.gettalong.org/syntax.html

<!--
vim: ts=2 expandtab :
-->